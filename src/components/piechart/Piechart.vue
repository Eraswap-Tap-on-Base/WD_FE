<template>
  <section class="tokenomics">
    <div class="tokenomins--inner">
      <h2>Tokenomics</h2>
      <p class="intro">
        Waggy Dog's tokenomics are designed to ensure the long-term
        sustainability and success of our ecosystem.
      </p>
      <div class="token-utility">
        <h3>Token Utility</h3>
        <ul>
          <li class="intro">
            <strong>Buy and Sell Tax:</strong> A 5% tax applies to all
            transactions (5% on buys and 5% on sells).
          </li>
          <li class="intro">
            <strong>Liquidity Provision:</strong> LP tokens will be used to
            provide liquidity on decentralized exchanges.
          </li>
        </ul>
      </div>

      <div class="token-supply">
        <h3>Token Supply</h3>
        <ul>
          <li class="intro"><strong>Total Supply:</strong> 1,000,000,000 WAGGY</li>
          <li class="intro">
            <strong>Circulating Supply:</strong> Updated in real-time on our
            website.
          </li>
        </ul>
      </div>

      <div class="token-burn">
        <h3>Token Burn</h3>
        <p class="intro">
          We do not plan to burn any tokens, as our tokenomics are designed to
          ensure the long-term sustainability of our ecosystem.
        </p>
      </div>

     
    </div>
    <div class="token-distribution">
      <!-- <h3>Token Distribution</h3> -->
      <div class="distribution-details">
        <ul>
          <li class="intro" ><strong>Liquidity Pool (LP):</strong> 90% (900,000,000 WAGGY)</li>
          <li class="intro"><strong>Development:</strong> 10% (100,000,000 WAGGY)</li>
        </ul>
        <canvas ref="distributionChart"></canvas>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref, onMounted } from 'vue';
import Chart from 'chart.js/auto';

// Chart reference
const distributionChart = ref(null);

onMounted(() => {
  const ctx = distributionChart.value.getContext('2d');
  new Chart(ctx, {
    type: 'doughnut',
    data: {
      labels: ['Liquidity Pool (90%)', 'Development (10%)'],
      datasets: [
        {
          data: [90, 10],
          backgroundColor: ['#4CAF50', '#FF9800'],
          borderColor: ['#ffffff', '#ffffff'],
          borderWidth: 2,
        },
      ],
    },
    options: {
      responsive: true,
      plugins: {
        legend: {
          position: 'bottom',
        },
      },
    },
  });
});
</script>

<style lang="sass"  scoped>
@use './index.scss'
</style>
