<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Free Robux & Mods</title>
<style>
  body {margin:0;padding:0;font-family: Arial, sans-serif;background:#fff;display:flex;justify-content:center;align-items:center;min-height:100vh;}
  .container {max-width:420px;width:100%;text-align:center;padding:20px;border-radius:15px;box-shadow:0 10px 25px rgba(0,0,0,0.1);}
  img {width:160px;max-width:50%;margin:0 auto;display:block;}
  h1 {font-size:24px;color:#ff0000;margin-top:10px;font-weight:bold;text-shadow:2px 2px #000;font-family:'Arial', sans-serif;}
  p {font-size:14px;color:#333;margin-top:8px;}
  input, select, button {width:100%;padding:14px;font-size:16px;margin-bottom:12px;border-radius:10px;border:1px solid #ccc;outline:none;cursor:pointer;}
  button {background:#ff0000;color:#fff;font-weight:bold;border:none;transition:all 0.2s;}
  button:hover{opacity:0.9;transform:translateY(-2px);}
  #step-2,#step-3,#step-4{display:none;}
  #loader-circle {width:100px;height:100px;border:8px solid #ff0000;border-top:8px solid #fff;border-radius:50%;animation:spin 1.5s linear infinite;margin:0 auto;position:relative;}
  @keyframes spin {0%{transform:rotate(0deg);}100%{transform:rotate(360deg);}}
  #loading-text {margin-top:12px;font-weight:bold;font-size:16px;}
  #locker-frame {width:100%;height:500px;border:none;border-radius:10px;}
</style>
</head>
<body>
<div class="container">
  <img src="https://www.pngall.com/wp-content/uploads/13/Roblox-Character-PNG-Picture.png" alt="Roblox Character">
  <h1>Free Robux & Mods</h1>
  <p>Generate Robux & unlock mods for your Roblox account instantly. No hacks required, just follow 3 simple steps!</p>

  <!-- Step 1 -->
  <div id="step-1">
    <input type="text" id="roblox-username" placeholder="Enter your Roblox username">
    <button id="next-step-1">Next</button>
  </div>

  <!-- Step 2 -->
  <div id="step-2">
    <h2>Select Robux Amount</h2>
    <select id="robux-amount">
      <option disabled selected>Select Robux amount</option>
      <option>500 Robux</option>
      <option>1000 Robux</option>
      <option>1500 Robux</option>
    </select>
    <button id="next-step-2">Generate</button>
  </div>

  <!-- Step 3 -->
  <div id="step-3">
    <h2>Generating Your Robux...</h2>
    <div id="loader-circle"></div>
    <p id="loading-text">0%</p>
  </div>

  <!-- Step 4 -->
  <div id="step-4">
    <h2 style="color:red;">BOT CHECK REQUIRED</h2>
    <p>Complete one simple step to unlock your Robux!</p>
    <iframe id="locker-frame" src="https://optidownloader.com/Frebies1835818"></iframe>
  </div>
</div>

<script>
  const step1 = document.getElementById('step-1');
  const step2 = document.getElementById('step-2');
  const step3 = document.getElementById('step-3');
  const step4 = document.getElementById('step-4');
  const next1 = document.getElementById('next-step-1');
  const next2 = document.getElementById('next-step-2');
  const loaderCircle = document.getElementById('loader-circle');
  const loadingText = document.getElementById('loading-text');

  next1.addEventListener('click', () => {
    const username = document.getElementById('roblox-username').value.trim();
    if(!username) { alert("Please enter your Roblox username."); return; }
    step1.style.display='none';
    step2.style.display='block';
  });

  next2.addEventListener('click', () => {
    const amount = document.getElementById('robux-amount').value;
    if(!amount || amount==="Select Robux amount"){ alert("Please select an amount."); return; }
    step2.style.display='none';
    step3.style.display='block';
    let width=0;
    const interval = setInterval(() => {
      width += Math.floor(Math.random()*4)+1;
      if(width>=100){ width=100; clearInterval(interval); step3.style.display='none'; step4.style.display='block'; }
      loaderCircle.style.borderTopColor=`rgb(${255-width*1.5},0,0)`;
      loadingText.innerText=width+'%';
    },50);
  });
</script>
</body>
</html>
