<script context="module" lang="ts">
  export const prerender = true
</script>

<script lang="ts">
  import GitHubIcon from '$lib/icons/GitHubIcon.svelte'
  import LinkedInIcon from '$lib/icons/LinkedInIcon.svelte'
  import MailIcon from '$lib/icons/MailIcon.svelte'
</script>

<svelte:head>
  <title>Changyuan Lin</title>
</svelte:head>

<div class="icons">
  <a href="https://github.com/Coreball"><GitHubIcon title="Visit GitHub" /></a>
  <a href="https://www.linkedin.com/in/coreballium/"><LinkedInIcon title="Visit LinkedIn" /></a>
  <a href="mailto:cl859@cornell.edu"><MailIcon title="Email cl859@cornell.edu" /></a>
</div>

<p>Hi, I'm Changyuan Lin, a computer science student at Cornell University.</p>

<section>
  <h2>Currently</h2>
  <ul>
    <li>MEng Student at Cornell University</li>
    <li>Chillin' at Cornell DTI</li>
  </ul>
</section>

<section>
  <h2>Previously</h2>
  <ul>
    <li>Graduated summa from Cornell University with a BS in CS :)</li>
    <li>
      Technical Product Manager at <a href="https://www.cornelldti.org/">Cornell DTI</a>
      <ul>
        <li><a href="https://github.com/cornell-dti/zing">Grouper</a></li>
        <li><a href="https://github.com/cornell-dti/zing-lsc">Zing LSC</a></li>
      </ul>
    </li>
    <li>
      Developer at <a href="https://www.cornelldti.org/">Cornell DTI</a>
      <ul>
        <li><a href="https://github.com/cornell-dti/campus-density-ios">Flux iOS</a></li>
      </ul>
    </li>
    <li>Software Development Engineer Intern at Amazon Web Services</li>
    <li>Software Development Engineer Intern at Amazon Ads</li>
    <li>Instructor at Coding With Kids</li>
  </ul>
</section>

<section>
  <h2>Links</h2>
  <ul>
    <li><a href="https://github.com/Coreball">GitHub</a></li>
    <li><a href="https://www.linkedin.com/in/coreballium/">LinkedIn</a></li>
    <li><a href="mailto:cl859@cornell.edu">cl859@cornell.edu</a></li>
  </ul>
</section>

<style>
  section {
    margin: 0.5rem 0;
  }

  h2 {
    font-size: 1rem;
    margin: 0.5rem 0;
  }

  ul {
    margin: 0;
  }

  .icons {
    display: flex;
    gap: 1rem;
    margin: 1rem 0;
  }
</style>
