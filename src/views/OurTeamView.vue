<script setup>
import BioCard from "../components/BioCard.vue";
</script>

<template>
  <main class="flex OurTeam">
    <section class="fixed OurteamTxt">
      <h2 class="font-extrabold text-gray-200 text-6xl mt-32 ourTeamTitle">
        Meet the Team:
      </h2>
      <h3
        class="text-lg font-bold py-10 ourTeam-desc text-gray-300 OurTeamDesc"
      >

      This is the team of founders, developers, and teachers behind Programmatic. Our team is the driving force behind the continued development and improvement of Programmatic. With a blend of visionary founders, skilled developers, and creative educators, we are committed to providing excellent teaching materials, refining Programmatic, and creating impactful experiences for our students.
      </h3>
    </section>
    <section class="line"></section>
    <section class="flex flex-col gap-20 mt-36 mb-10 cards">
      <BioCard
        name="Ofir"
        pos="Founder, Front-End Developer, Teacher"
        desc="Hi, I'm Ofir, the founder of Programmatic. With over 5 years of coding experience, I specialize in Python and have recently started exploring Unity and Dart to create practical applications. I’m excited to help guide you through your programming journey!"
        langs="Python, Dart, C#, JavaScript"
        discord="@.ofish"
        imgurl="discord.png"
      />
      <BioCard
        name="Zain"
        desc="Hi, I’m Zain! I’m excited to teach you about programming. I have 3 years of experience working with both Python and Raspberry Pi, and I’m passionate about helping others learn to build their own tech projects."
        langs="Python, Raspberry Pi, Circuits"
        discord="@zkzain06"
        pos="Founder, Front-End Developer, Teacher"
        imgurl="discord.png"
      />

      <BioCard
        name="Adam"
        desc="Hello, I’m Adam. With about 4 years of experience in Unity, I specialize in game development. I’m here to help you understand how to bring your creative ideas to life through coding."
        langs="Python, C#"
        discord="@Adamimoka"
        pos="Founder, Graphic Designer, Front-End Developer"
        imgurl="discord.png"
      />

      <BioCard
        name="Ethan"
        desc="Hi, I’m Ethan! I work as a full-stack developer and maintain the Programmatic Discord bot. I also develop websites and applications to help your learning experience."
        langs="Python, C++, Java, JavaScript"
        discord="@ethqnol"
        pos="Full-Stack Developer, Dev of the Programmatic Discord Bot"
        imgurl="discord.png"
      />
    </section>
  </main>
</template>

<style scoped>
body {
  padding: 0;
  margin: 0;
}

.wrapper {
  display: flex;
}

nav {
  flex: 0 0 50vw;
  background: gray;
}

.nav-wrapper {
  position: fixed;
  top: 0;
  left: 0;
}

section {
  flex: 1 1;
}

/* media 1350 */

@media (max-width: 1350px) {
  .line {
    display: none;
  }

  .OurteamTxt {
    position: inherit;
  }

  .OurTeam {
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .cards {
    margin-top: 1rem;
  }

  .OurTeamDesc {
    width: 800px !important;
    max-width: 800px !important;
    text-align: center;
  }

  .ourTeamTitle {
    text-align: center;
  }

  /* media 1000px */
  @media (max-width: 1000px) {
    .OurTeamDesc {
      width: 600px !important;
      max-width: 600px !important;
    }
  }

  /* media 650px */
  @media (max-width: 650px) {
    .OurTeamDesc {
      width: 400px !important;
      max-width: 400px !important;
    }
  }

  /* media 450px */
  @media (max-width: 450px) {
    .OurTeamDesc {
      width: 370px !important;
      max-width: 370px !important;
    }
  }
}
</style>
