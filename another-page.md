---
layout: default
title: Salary Hike Calculator 
description: Cal
---

## Welcome to another page

<section class="flex flex-col items-center justify-center min-h-screen bg-gray-100 py-6">
<div class="mockup-window w-full lg:w-3/4 xl:w-5/6 mx-auto lg:mt-16 border border-base-300 rounded-box shadow-lg">
  <div class="flex flex-col lg:flex-row justify-between items-center px-4 py-8 lg:px-8 lg:py-12 border-b border-base-300">
    <div class="w-full lg:w-7/12">
      <div class="p-6 flex-grow">
        <h2 class="text-xl font-bold mb-2">Salary Hike Calculator</h2>
        <div class="form-control">
          <label class="label">
            <span class="label-text">Current Salary</span>
          </label>
          <label class="input-group">
            <span class="input-group-addon">₹</span>
            <input type="number" id="current-salary" placeholder="Enter current salary" class="input input-bordered" />
          </label>
           <input type="range" id="current-salary-range" min="100000" max="5000000" step="100000" value="100000" class="range range-xs mt-5" />
        </div>
        <div class="form-control">
          <label class="label">
            <span class="label-text">Percentage Hike</span>
          </label>
          <label class="input-group">
            <input type="number" id="percentage-hike" placeholder="Enter percentage hike" class="input input-bordered" />
            <span class="input-group-addon">%</span>
          </label>
        </div>
        <button class="btn btn-primary mt-4" onclick="calculateSalary()">Calculate</button>
      </div>
    </div>
    <div class="w-full lg:w-4/12 mt-8 lg:mt-0">
      <div class="stats stats-vertical shadow">
        <div class="stat">
          <div class="stat-title">Current Salary</div>
          <div class="stat-value">₹0</div>
        </div>
        <div class="stat">
          <div class="stat-title">Percentage Hike</div>
          <div class="stat-value">0%</div>
        </div>
        <div class="stat">
          <div class="stat-title">Hike Amount</div>
          <div class="stat-value">₹0</div>
        </div>
        <div class="stat">
          <div class="stat-title">New Salary</div>
          <div class="stat-value">₹0</div>
        </div>
      </div>
    </div>
  </div>
</div>
</section>

  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-1291242080282540"
     crossorigin="anonymous"></script>
<!-- The Leaderboard (728×90) -->
<ins class="adsbygoogle"
     style="display:inline-block;width:728px;height:90px"
     data-ad-client="ca-pub-1291242080282540"
     data-ad-slot="1864856299"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>


<div class="card shadow-lg p-6">
  <h2 class="mb-4 text-2xl font-bold">How to Use the Salary Hike Calculator</h2>
  <div class="step step-info step-lg">
    <div class="step-content">
      <h3 class="mb-2 font-bold">Step 1</h3>
      <p class="mb-4">Enter your current salary in the first field.</p>
      <div class="mb-2">
        <label for="current-salary" class="form-label">Current Salary:</label>
        <input type="number" id="current-salary" class="form-input" placeholder="Enter your current salary" />
      </div>
    </div>
  </div>
  <div class="step step-info step-lg">
    <div class="step-content">
      <h3 class="mb-2 font-bold">Step 2</h3>
      <p class="mb-4">Enter the percentage increase you expect to receive in the second field.</p>
      <div class="mb-2">
        <label for="percentage-increase" class="form-label">Percentage Increase:</label>
        <input type="number" id="percentage-increase" class="form-input" placeholder="Enter expected percentage increase" />
      </div>
    </div>
  </div>
  <div class="step step-info step-lg">
    <div class="step-content">
      <h3 class="mb-2 font-bold">Step 3</h3>
      <p class="mb-4">Click the "Calculate" button to see your new salary.</p>
      <button class="btn btn-primary">Calculate</button>
    </div>
  </div>
</div>

[def]: ./
[back][def]


