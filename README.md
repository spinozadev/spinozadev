<div align="center">
  <h3>Hello friend, I'm <span style="font-size: 1.5em;">Spinoza.</span></h3>
  <h5 style="font-size: 1.2em;">{ <span id="dynamicText"></span> }</h5>

  <p>
    <a href="https://discord.com/users/119788257859993601"><img alt="Discord" title="Discord" src="https://img.shields.io/badge/-Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white"/></a>
    <a href="https://instagram.com/spinozapy" target="_blank"><img src="https://img.shields.io/badge/INSTAGRAM%20-DC3175.svg?&style=for-the-badge&logo=instagram&logoColor=white"></a>
  </p>
  <div style="width: 200px; text-align: center;">
    <img src="https://komarev.com/ghpvc/?username=spinozapy&color=blueviolet&style=plastic&label=Profile+Views:" alt="Profile Views">
  </div>
</div>

<script>
  const texts = ["explorer", "creator", "dreamer", "thinker"];
  let counter = 0;
  const dynamicTextElement = document.getElementById('dynamicText');
  
  function changeText() {
    dynamicTextElement.textContent = texts[counter];
    counter = (counter + 1) % texts.length;
  }

  setInterval(changeText, 555); // Change text every second
</script>
