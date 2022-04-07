<script setup>
import HomeListItem from './HomeListItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <HomeListItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Career</template>

    Senior Platform Engineer @ <a href="https://cts.co">CTS</a> (2018-2022)
  </HomeListItem>

  <HomeListItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Learning</template>

    BSc in Business Information Technology from <a href="https://aber.ac.uk">Aberystwyth University</a>.

    <br />
    GCP Professional Architect
    <br />
    GCP Professional DevOps Engineer
    <br />
    Certified Kubernetes Administrator
    <br />
    Certified Kubernetes Security Specialist
  </HomeListItem>

  <HomeListItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Contacts</template>

    <a target="_blank" href="https://twitter.com/markgingerninja/">Twitter</a><br />
    <a target="_blank" href="https://linkedin.com/in/mark-l-0a8917116//">LinkedIn</a><br />
    <a target="_blank" href="https://github.com/mark-lightfoot/">Github</a><br />
    <a target="_blank" href="mailto:mark@gingerninja.co">Email</a><br />
  </HomeListItem>

  <HomeListItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Interests</template>

    <ul>
      <li>Kubernetes</li>
      <li>DevOps, SRE and helping Engineers</li>
      <li>Solving complex problems and Architectures</li>
      <li>Mentoring/Helping/Inspiring</li>
      <li>Aviation, the RAF and shooting</li>
      <li>Most importantly, Star Wars.</li>
    </ul>
  </HomeListItem>

  <HomeListItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>WIP!!</template>

    The site is WIP. If you know Vue, you can probably see I havent even changed from the bootstrap. Im still learning.
  </HomeListItem>
</template>
