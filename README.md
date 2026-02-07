<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Predictions</title>
<style>
  * { margin:0; padding:0; box-sizing:border-box; font-family: Arial, Helvetica, sans-serif; }

  body {
    background-color: #e0f7ff; /* Light blue background */
    color: #1e293b;
    padding: 4px; /* Ultra tight padding */
  }

  table {
    width: 100%;
    border-collapse: collapse;
    table-layout: fixed; /* Fits small screens */
    font-size: 11px; /* Small but readable */
  }

  th, td {
    padding: 2px 3px; /* Tiny padding for max compactness */
    text-align: center;
    word-wrap: break-word; 
  }

  th {
    background-color: #0ea5e9;
    color: #fff;
    font-size: 12px;
  }

  tr:nth-child(even) { background-color: #bae6fd; }
  tr:nth-child(odd)  { background-color: #d0f0ff; }

  .pick { color: #2563eb; font-weight: bold; font-size: 11px; }

  .win { color: #16a34a; font-weight: bold; font-size: 11px; }
  .loss { color: #dc2626; font-weight: bold; font-size: 11px; }
  .pending { color: #fbbf24; font-weight: bold; font-size: 11px; }

</style>
</head>
<body>

<table>
  <tr>
    <th>Date</th>
    <th>Match</th>
    <th>Pick</th>
    <th>Result</th>
  </tr>

  <tr>
    <td>10/02/26</td>
    <td>Barcelona vs Real Madrid</td>
    <td class="pick">Over 3.5</td>
    <td class="win">WIN</td>
  </tr>

  <tr>
    <td>09/02/26</td>
    <td>Liverpool vs Man City</td>
    <td class="pick">B.T.T.S</td>
    <td class="pending">PENDING</td>
  </tr>

  <tr>
    <td>08/02/26</td>
    <td>Juventus vs Inter</td>
    <td class="pick">Over 2.5</td>
    <td class="loss">LOSS</td>
  </tr>

  <tr>
    <td>07/02/26</td>
    <td>PSG vs Lyon</td>
    <td class="pick">B.T.T.S</td>
    <td class="win">WIN</td>
  </tr>

  <tr>
    <td>06/02/26</td>
    <td>Man Utd vs Fulham</td>
    <td class="pick">Over 3.5</td>
    <td class="win">WIN</td>
  </tr>

  <tr>
    <td>05/02/26</td>
    <td>Atletico vs Sevilla</td>
    <td class="pick">Over 2.5</td>
    <td class="pending">PENDING</td>
  </tr>

  <tr>
    <td>04/02/26</td>
    <td>Chelsea vs Arsenal</td>
    <td class="pick">Over 3.5</td>
    <td class="win">WIN</td>
  </tr>

</table>

</body>
</html>
