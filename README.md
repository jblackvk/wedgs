# wedgs

Bienvenu <span id="username"></span>, Cher Invite au mariage de Gilles et Sandra.

Cette page vous signale que votre invitation est valide.

Passez une bonne soiree

<Script>
  var usernameZone = document.getElementById('username');
  const urlParams = new URLSearchParams(window.location.search);
  const nom =params.get('name');
  console.log(nom);
  if (nom){
      usernameZone.textcontent = urlParams;
  }
</Script>
