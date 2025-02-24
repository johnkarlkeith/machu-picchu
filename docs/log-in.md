# Macchu Pichu

**Target:** TBD

---

<table>
  <tr>
    <td valign="top" style="width: 35%;">
      <h2>Site Map</h2>
      <a href="#">Revisions</a><br><br>     
      Admin Homepage<br>
      &nbsp;&nbsp;<a href="/docs/New Text Document.txt">Sign in</a><br>
      &nbsp;&nbsp;<a href="#">Sign up</a><br><br>
      Products Page<br>
      &nbsp;&nbsp;<a href="#">Add item</a><br>
      &nbsp;&nbsp;<a href="#">Edit item</a><br>
      &nbsp;&nbsp;<a href="#">Delete item</a><br>
      &nbsp;&nbsp;<a href="#">Add inventory</a><br>
      &nbsp;&nbsp;<a href="#">Browse inventories</a><br>
      &nbsp;&nbsp;<a href="#">Edit inventory</a><br>
      &nbsp;&nbsp;<a href="#">Delete inventory</a><br>
      &nbsp;&nbsp;<a href="#">Add category</a><br>
      &nbsp;&nbsp;<a href="#">Edit category</a><br>
      &nbsp;&nbsp;<a href="#">Delete category</a><br>
      &nbsp;&nbsp;<a href="#">Add supplier</a><br>
      &nbsp;&nbsp;<a href="#">Edit supplier</a><br>
      &nbsp;&nbsp;<a href="#">Delete supplier</a><br>
      &nbsp;&nbsp;<a href="#">Create Inventory Report</a><br><br>
      Finance Page<br>
      &nbsp;&nbsp;<a href="#">Create Report</a><br>
      &nbsp;&nbsp;<a href="#">Create Audit</a><br><br>
      Accounts Page<br>
      &nbsp;&nbsp;<a href="#">Create Admin Account</a><br><br>
    </td>
    <td valign="top" >
      <h6> Admin Homepage > Sign in </h6>
        <img src = "./log-in.png" />
      <h3>Sign in</h3>
      <p>This serves as the main authentication page for admins to access the Honesty Store.</p>
      <table border="1">
        <tr>
          <th>Use Case</th>
          <th>Sign in</th>
        </tr>
        <tr>
          <td><b>Actors</b></td>
          <td>User (Primary), System (Secondary)</td>
        </tr>
        <tr>
          <td><b>Preconditions</b></td>
          <td>User must have an existing account</td>
        </tr>
        <tr>
          <td>Triggers</td>
          <td>User clicks the 'Sign In' button.</td>
        </tr>
        <tr>
          <td><b>Basic Flow</b></td>
          <td>
            <ol>
              <li>User enters email & password.</li>
              <li>User clicks 'Sign-in'</li>
              <li>System validates credentials</li>
              <li>If valid, system redirects to the admin dashboard</li>
            </ol>
          </td>
        </tr>
        <tr>
          <td><b>Alternative Flow</b></td>
          <td><strong>Invalid Credentials</strong>: System shows an error message</td>
        </tr>
        <tr>
          <td><b>Postconditions</b></td>
          <td>User is logged in and can access their account.</td>
        </tr>
        <tr>
          <td><b>Exceptions</b></td>
          <td>Server is down → System shows error message</td>
        </tr>
        </table>
    </td>
  </tr>
</table>

---

<div align="center">
  © 2025 <a href="#">NexTech</a>
</div>
