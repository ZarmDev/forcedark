function darkMode() {
  document.body.style = 'background-color: #ffd5dc; transition: 0.5s; color: #e48a9b !important;';
  // #ffffff
  // #bf8891
  document.getElementById('container').style = 'background-color: #a94545 !important;';
  for (var i = 0; i < document.getElementsByTagName('nav').length; i++) {
    document.getElementsByTagName('nav')[i].style = 'background-color: #a94545 !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('header').length; i++) {
    document.getElementsByTagName('header')[i].style = 'background-color: #fbe5e5 !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('section').length; i++) {
    document.getElementsByTagName('section')[i].style = 'background-color: #f9d4d4 !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('article').length; i++) {
    document.getElementsByTagName('article')[i].style = 'background-color: white !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('aside').length; i++) {
    document.getElementsByTagName('aside')[i].style = 'background-color: white !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('footer').length; i++) {
    document.getElementsByTagName('footer')[i].style = 'background-color: white !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('a').length; i++) {
    document.getElementsByTagName('a')[i].style = 'color: #e48a9b !important; text-decoration: none !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('span').length; i++) {
    document.getElementsByTagName('span')[i].style = 'color: #e48a9b !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('p').length; i++) {
    document.getElementsByTagName('p')[i].style = 'color: #e48a9b !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('code').length; i++) {
    document.getElementsByTagName('code')[i].style = 'color: rgba(255, 0, 0, 0.6) !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('h1').length; i++) {
    document.getElementsByTagName('h1')[i].style = 'color: #f74040 !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('h2').length; i++) {
    document.getElementsByTagName('h2')[i].style = 'color: #f74040 !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('h3').length; i++) {
    document.getElementsByTagName('h3')[i].style = 'color: #f74040 !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('h4').length; i++) {
    document.getElementsByTagName('h4')[i].style = 'color: #f74040 !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('h5').length; i++) {
    document.getElementsByTagName('h5')[i].style = 'color: #f74040 !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('h6').length; i++) {
    document.getElementsByTagName('h6')[i].style = 'color: #f74040 !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('ul').length; i++) {
    document.getElementsByTagName('ul')[i].style = 'color: #ff96a8 !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('i').length; i++) {
    document.getElementsByTagName('i')[i].style = 'background-color: deeppink; border-radius: 5px; padding: 1vw;';
  }
  /*
  document.body.style = 'background-color: black; transition: 0.5s;';
  for (var i = 0; i < document.getElementsByTagName('div').length; i++) {
    document.getElementsByTagName('div')[i].style = 'background-color: rgb(46, 47, 70) !important; color: white;';
  }
  for (var i = 0; i < document.getElementsByTagName('p').length; i++) {
    document.getElementsByTagName('p')[i].style = '#ffffffc7';
  }
  for (var i = 0; i < document.getElementsByTagName('a').length; i++) {
    document.getElementsByTagName('a')[i].style = 'color: #f7f7f7 !important; text-decoration: none !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('h1').length; i++) {
    document.getElementsByTagName('h1')[i].style = 'white';
  }
  for (var i = 0; i < document.getElementsByTagName('h2').length; i++) {
    document.getElementsByTagName('h2')[i].style = '#e4e4e4';
  }
  for (var i = 0; i < document.getElementsByTagName('img').length; i++) {
    document.getElementsByTagName('img')[i].style = 'border: solid white 4px; border-radius: 5px;';
  }
  for (var i = 0; i < document.getElementsByTagName('ul').length; i++) {
    document.getElementsByTagName('ul')[i].style = 'white';
  }
  for (var i = 0; i < document.getElementsByTagName('span').length; i++) {
    document.getElementsByTagName('span')[i].style = 'color: #ffffffc7 !important; background-color: rgb(0, 0, 0, 0)';
  }
  for (var i = 0; i < document.getElementsByTagName('nav').length; i++) {
    document.getElementsByTagName('nav')[i].style = 'background-color: rgb(46, 47, 70) !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('button').length; i++) {
    document.getElementsByTagName('button')[i].style = 'color: white !important; background-color: #0366d6; border-radius: 5px;';
  }
  for (var i = 0; i < document.getElementsByTagName('code').length; i++) {
    document.getElementsByTagName('code')[i].style = 'background-color: rgb(46, 47, 70);';
  }
  for (var i = 0; i < document.getElementsByTagName('summary').length; i++) {
    document.getElementsByTagName('summary')[i].style = 'background-color: rgb(46, 47, 70);';
  }
  for (var i = 0; i < document.getElementsByTagName('h3').length; i++) {
    document.getElementsByTagName('h3')[i].style = 'white';
  }
  for (var i = 0; i < document.getElementsByTagName('h4').length; i++) {
    document.getElementsByTagName('h4')[i].style = 'white';
  }
  for (var i = 0; i < document.getElementsByTagName('h5').length; i++) {
    document.getElementsByTagName('h5')[i].style = 'white';
  }
  for (var i = 0; i < document.getElementsByTagName('h6').length; i++) {
    document.getElementsByTagName('h6')[i].style = 'white';
  }
  for (var i = 0; i < document.getElementsByTagName('header').length; i++) {
    document.getElementsByTagName('header')[i].style = 'background-color: rgb(46, 47, 70) !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('nav').length; i++) {
    document.getElementsByTagName('nav')[i].style = 'background-color: rgb(46, 47, 70) !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('section').length; i++) {
    document.getElementsByTagName('section')[i].style = 'background-color: rgb(46, 47, 70) !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('article').length; i++) {
    document.getElementsByTagName('article')[i].style = 'background-color: rgb(46, 47, 70) !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('aside').length; i++) {
    document.getElementsByTagName('aside')[i].style = 'background-color: rgb(46, 47, 70) !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('footer').length; i++) {
    document.getElementsByTagName('footer')[i].style = 'background-color: rgb(46, 47, 70) !important;';
  }
  for (var i = 0; i < document.getElementsByTagName('yt-formatted-string').length; i++) {
    document.getElementsByTagName('yt-formatted-string')[i].style = 'color: white !important;';
  }
  document.getElementById('contents').style = 'white';
  */
}

chrome.action.onClicked.addListener((tab) => {
  chrome.scripting.executeScript({
    target: { tabId: tab.id },
    function: darkMode
  });
});