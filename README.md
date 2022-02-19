# noble-prize-winners
Bikayi assignment

fetch(': http://api.nobelprize.org/v1/prize.json')
  .then(response => response.json())
  .then(data => console.log(data));
