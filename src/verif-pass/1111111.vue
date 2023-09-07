<template>
  <div class="confirmation-container">
    <table>
      <th colspan="3">קבלה על תשלום מס תיירות - Tourist Tax Payment Confirmation</th>
      <tr>
        <td class="ri">תאריך תשלום</td>
        <td class="cent">2023-09-04</td>
        <td class="lef">Date of payment</td>
      </tr>
      <tr>
        <td class="ri">שם פרטי</td>
        <td class="cent">Rudy</td>
        <td class="lef">First Name</td>
      </tr>
      <tr>
        <td class="ri">שם משפחה</td>
        <td class="cent">Garcin</td>
        <td class="lef">Last Name</td>
      </tr>
      <tr>
        <td class="ri">מספר דרכון</td>
        <td class="cent">21cf91446</td>
        <td class="lef">Passport Number</td>
      </tr>
      <tr>
        <td class="ri">תאריך לידה</td>
        <td class="cent">21/08/1981</td>
        <td class="lef">Date Of Birth</td>
      </tr>
      <tr>
        <td class="ri">על סך</td>
        <td class="cent">27$</td>
        <td class="lef">Amount Paid</td>
      </tr>
    </table>
  </div>
</template>

<style>
body {
  text-align: center;
}
.confirmation-container {
  width: 100%;
  max-width: 600px; /* Adjust the maximum width as needed */
  margin: 20px auto;
  padding: 20px;
  direction: rtl;
  font-weight: bolder;
}
table {
  width: 100%;
  border-collapse: collapse;
}
th,
td {
  border: 1px solid #000;
  padding: 8px;
  font-weight: bold;
}
.ri {
  text-align: right;
}
.cent {
  text-align: center;
}
.lef {
  text-align: left;
}
th {
}
</style>
<script setup lang="ts"></script>
