---
title: Decision
permalink: /resources-for-practitioners/decision/
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

#myInput {
  background-image: url('/css/searchicon.png');
  background-position: 10px 10px;
  background-repeat: no-repeat;
  width: 100%;
  font-size: 16px;
  padding: 12px 20px 12px 40px;
  border: 1px solid #ddd;
  margin-bottom: 12px;
}

#myTable {
  border-collapse: collapse;
  width: 100%;
  border: 1px solid #ddd;
  font-size: 18px;
}

#myTable th, #myTable td {
  text-align: left;
  padding: 12px;
}

#myTable tr {
  border-bottom: 1px solid #ddd;
}

#myTable tr.header, #myTable tr:hover {
  background-color: #f1f1f1;
}
</style>
</head>
<body>

<h2>Judgements</h2>

You can use this tool to search for decisions by t <p>

Citation <input type="text" id="myInput1" onkeyup="myFunction1()" placeholder="Search for citation.." title="Type in a citation">
<p>

Authority <input type="text" id="myInput2" onkeyup="myFunction2()" placeholder="Search by authority.." title="Type in an authority">
<p>
Type of IP <input type="text" id="myInput3" onkeyup="myFunction3()" placeholder="Search by IP.." title="Type in an IP">
<p>
Type of Action <input type="text" id="myInput4" onkeyup="myFunction4()" placeholder="Search by type of action.." title="Type in a type of action">
<p>
Year <input type="text" id="myInput5" onkeyup="myFunction5()" placeholder="Search by year.." title="Type in year">

<p>

<table id="myTable">
  <tr class="header">
    <th style="width:60%;">Citation</th>
    <th style="width:10%;">Authority</th>
    <th style="width:10%;">Type of IP</th>
    <th style="width:10%;">Type of Action</th>
    <th style="width:10%;">Year</th>
    
  </tr>
  <tr>
    <td><a href="https://www.singaporelawwatch.sg/Portals/0/Docs/Judgments/2020/[2020]%20SGIPOS%2012.pdf">Application to File Notice of Opposition in a Geographical Indication Application by Bavaria N.V. and Objection Thereto by Bayerischer Brauerbund E.V. [2020] SGIPOS 12 </a></td>
    <td>IPOS</td>
    <td>Geographical Indication</td>
    <td>Interlocutory Hearing</td>
    <td>2020</td>
  </tr>
  <tr>
    <td><a href="https://www.ipos.gov.sg/docs/default-source/hmd-library/case-(abf19dc9-130c-4ad8-9202-76370076da9d)/decision-files/damiani-international-v-dhamani-jewels-dmcc-2020-sgipos-11.pdf?Status=Master&sfvrsn=20267859_0">Damiani International BV v Dhamani Jewels DMCC [2020] SGIPOS 11</a></td>
     <td>High Court</td>
    <td>Trade Mark</td>
    <td>Opposition</td>
    <td>2019</td>
  </tr>
    <tr>
<td><a href="Comité Interprofessionnel du Vin de Champagne and Institut National de l’Origine et de la Qualité v Keep Waddling International Pte. Ltd. [2020] SGIPOS 10">Comité Interprofessionnel du Vin de Champagne and Institut National de l’Origine et de la Qualité v Keep Waddling International Pte. Ltd. [2020] SGIPOS 10</a></td>
     <td>High Court</td>
    <td>Trade Mark</td>
    <td>Opposition</td>
    <td>2020</td>
  </tr>
 </table>

<script>
function myFunction1() {
  var input, input2, filter, table, tr, td, td2, i, txtValue;
  input = document.getElementById("myInput1");
  filter = input.value.toUpperCase();
  table = document.getElementById("myTable");
  tr = table.getElementsByTagName("tr");
  for (i = 0; i < tr.length; i++) {
    td = tr[i].getElementsByTagName("td")[0]; 
    if (td) {
      txtValue = td.textContent || td.innerText;
      if (txtValue.toUpperCase().indexOf(filter) > -1) {
        tr[i].style.display = "";
      }else{
        tr[i].style.display = "none";
      }
    }       
  }
}
function myFunction2() {
  var input, filter, table, tr, td, i, txtValue;
  input = document.getElementById("myInput2");
  filter = input.value.toUpperCase();
  table = document.getElementById("myTable");
  tr = table.getElementsByTagName("tr");
  for (i = 0; i < tr.length; i++) {
    td = tr[i].getElementsByTagName("td")[1];
    if (td) {
      txtValue = td.textContent || td.innerText;
      if (txtValue.toUpperCase().indexOf(filter) > -1) {
        tr[i].style.display = "";
      } else {
        tr[i].style.display = "none";
      }
    }       
  }
}
function myFunction3() {
  var input, filter, table, tr, td, i, txtValue;
  input = document.getElementById("myInput3");
  filter = input.value.toUpperCase();
  table = document.getElementById("myTable");
  tr = table.getElementsByTagName("tr");
  for (i = 0; i < tr.length; i++) {
    td = tr[i].getElementsByTagName("td")[2];
    if (td) {
      txtValue = td.textContent || td.innerText;
      if (txtValue.toUpperCase().indexOf(filter) > -1) {
        tr[i].style.display = "";
      } else {
        tr[i].style.display = "none";
      }
    }       
  }
}
function myFunction4() {
  var input, filter, table, tr, td, i, txtValue;
  input = document.getElementById("myInput4");
  filter = input.value.toUpperCase();
  table = document.getElementById("myTable");
  tr = table.getElementsByTagName("tr");
  for (i = 0; i < tr.length; i++) {
    td = tr[i].getElementsByTagName("td")[3];
    if (td) {
      txtValue = td.textContent || td.innerText;
      if (txtValue.toUpperCase().indexOf(filter) > -1) {
        tr[i].style.display = "";
      } else {
        tr[i].style.display = "none";
      }
    }       
  }
}
function myFunction5() {
  var input, filter, table, tr, td, i, txtValue;
  input = document.getElementById("myInput5");
  filter = input.value.toUpperCase();
  table = document.getElementById("myTable");
  tr = table.getElementsByTagName("tr");
  for (i = 0; i < tr.length; i++) {
    td = tr[i].getElementsByTagName("td")[4];
    if (td) {
      txtValue = td.textContent || td.innerText;
      if (txtValue.toUpperCase().indexOf(filter) > -1) {
        tr[i].style.display = "";
      } else {
        tr[i].style.display = "none";
      }
    }       
  }
}
</script>

</body>
</html>
