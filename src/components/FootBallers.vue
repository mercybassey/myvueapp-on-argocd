<template>
  <div class="football-players">
    <table>
    <tr>
      <th>Footballer</th>
      <th>Age</th>
      <th>Country</th>
      <th>Club</th>
    </tr>
    <tr>
      <td>Cristiano Ronaldo</td>
      <td>37</td>
      <td>Portugal</td>
      <td>Man Utd</td>
    </tr>
    <tr>
      <td>Trent Alexander-Arnold</td>
      <td>23</td>
      <td>England</td>
      <td>Liverpool</td>
    </tr>
    <tr>
      <td>Karim Benzema</td>
      <td>34</td>
      <td>France</td>
      <td>Real Madrid</td>
    </tr>
    <tr>
      <td>Lionel Messi</td>
      <td>34</td>
      <td>Argentina</td>
      <td>PSG</td>
    </tr>
    <tr>
      <td>Robert Lewandowski</td>
      <td>33</td>
      <td>Poland</td>
      <td>Bayern Munich</td>
    </tr>
    <tr>
      <td>Kevin De Bruyne </td>
      <td>30</td>
      <td>Belgium</td>
      <td>Man City</td>
    </tr>
</table>
</div>
</template> 

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Source+Code+Pro:wght@200&display=swap');
table {
  font-family: 'Source Code Pro', monospace;
  border-collapse: collapse;
  border-radius: 10px;
  width: 100%;
}

td, th {
  border: 1px solid #dddddd;
  text-align: left;
  padding: 10px;
}

tr:nth-child(even) {
  background-color: #dddddd;
}
</style>