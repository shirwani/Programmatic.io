<script setup>
import AboutItem from "./AboutItem.vue";
</script>

<template>
  <AboutItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Who Are We?</template>
    We are a nonprofit organization dedicated to offering free computer science education through classes held at middle schools and libraries. With locations in Stowe and Sudbury, we aim to make computer science accessible to all. Our courses provide an opportunity for students to explore their interest in technology and build valuable skills. 
    <a class="text-blue-500" href="#/team" type="link"><u> our team</u>.</a>
  </AboutItem>

  <AboutItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Goals</template>

    At the heart of our mission is a commitment to helping students develop a curiosity for computer science and equip them with the essential skills needed to thrive in a tech-driven world. We are passionate about fostering a generation of individuals who are confident and capable in navigating the digital landscape, opening doors for personal and professional growth.
  </AboutItem>
  <AboutItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Programs & Classes</template>

    Our classes are designed for anyone eager to learn programming, from beginners to those looking to deepen their skills. Parents who value teaching their children early technological and problem-solving skills will find our programs to be a worthwhile investment. We offer a range of comprehensive courses, including Unity, Raspberry Pi, Python, and more! Find out more here.
    <a class="text-blue-500" href="#/enroll" type="link"><u>here</u>.</a>
  </AboutItem>
  <AboutItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Future</template>

    As we continue expanding our reach, we aim to offer even more diverse and accessible computer science programs. Our goal is to broaden our curriculum, offering a variety of programming concepts to suit the varied interests and backgrounds of students. We are committed to making our resources available to as many students as possible.
  </AboutItem>
  <AboutItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Donations</template>

    Support our mission 
    <a
      class="text-blue-500"
      href="https://hcb.hackclub.com/donations/start/programmatic"
      type="link"
      ><u>here</u></a
    >, to provide free computer science education to all. Any donation, no matter the size, helps keep our programs accessible. Every dollar directly supports the resources, tools, and materials that help our students succeed.
  </AboutItem>
</template>
