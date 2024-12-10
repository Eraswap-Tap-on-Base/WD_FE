<template>
    <section class="roadmap">
      <h1 class="roadmap-title">Waggy Dog Roadmap</h1>
      <div class="timeline">
        <div v-for="(phase, index) in roadmapPhases" :key="index" class="timeline-phase">
          <div class="phase-header" @click="togglePhase(index)">
            <h2>{{ phase.title }}</h2>
            <button class="toggle-btn">{{ activePhase === index ? '-' : '+' }}</button>
          </div>
          <transition name="fade">
            <ul v-if="activePhase === index" class="phase-details">
              <li v-for="(detail, idx) in phase.details" :key="idx">
                {{ detail }}
              </li>
            </ul>
          </transition>
        </div>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    data() {
      return {
        activePhase: null,
        roadmapPhases: [
          {
            title: "Q1-Q3 2024 (January-September)",
            details: [
              "Project Conceptualization: Develop the concept and idea behind Waggy Dog.",
              "Team Formation: Assemble a team of developers, marketers, and designers.",
              "Token Development: Design and develop the Waggy Dog token.",
              "Community Building: Establish social media presence, Discord server, and Telegram group.",
              "Partnership Development: Collaborate with influencers, content creators, and other blockchain projects.",
            ],
          },
          {
            title: "Q4 2024 (October-December)",
            details: [
              "Token Generation Event (TGE): Conduct a fair launch with 90% of tokens allocated to Liquidity Pool (LP) and 10% for development.",
              "Token Listing: List Waggy Dog tokens on decentralized exchanges (DEXs).",
              "Liquidity Pool Establishment: Establish liquidity pools on multiple DEXs.",
              "Community Engagement: Host AMAs, contests, and giveaways to engage the community.",
            ],
          },
          {
            title: "2025 and Beyond",
            details: [
              "Ecosystem Expansion: Develop and launch new features, tools, and services.",
              "Partnership Expansion: Foster alliances with industry leaders and other blockchain projects.",
              "Regulatory Compliance: Ensure adherence to regulatory requirements.",
              "Long-Term Sustainability: Ensure Waggy Dog's long-term viability and growth.",
            ],
          },
        ],
      };
    },
    methods: {
      togglePhase(index) {
        this.activePhase = this.activePhase === index ? null : index;
      },
    },
  };
  </script>
  
  <style lang="sass"  scoped>
@use './index.scss'
</style>