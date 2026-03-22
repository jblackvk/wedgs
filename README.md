# wedgs

Bienvenu <span id="username"></span>, Cher Invite au mariage de Gilles et Sandra.

Cette page vous signale que votre invitation est valide.

Passez une bonne journee / soiree

<Script>
  var usernameZone = document.getElementById("username");
  const urlParams = new URLSearchParams(window.location.search);
  const nom =urlParams.get('name');
  const id =urlParams.get('id');
  console.log(nom);
  console.log(urlParams);
  if (nom){
      usernameZone.textcontent = nom;
  }
  console.log(id);
</Script>
