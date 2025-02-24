# Macchu Pichu

**Target:** TBD

---

<table>
  <tr>
    <td valign="top" style="width: 35%;">
      <h2>Site Map</h2>
      <a href="../readme.md">Revisions</a><br><br>     
      Admin Homepage<br>
      &nbsp;&nbsp;<a href="./sign-in.md">Sign in</a><br><br>
      Products Page<br>
      &nbsp;&nbsp;<a href="./add-item.md">Add item</a><br>
      &nbsp;&nbsp;<a href="./edit-item.md">Edit item</a><br>
      &nbsp;&nbsp;<a href="./delete-item.md">Delete item</a><br>
      &nbsp;&nbsp;<a href="./add-inventory.md">Add inventory</a><br>
      &nbsp;&nbsp;<a href="./browse-inventory.md">Browse inventories</a><br>
      &nbsp;&nbsp;<a href="./edit-inventory.md">Edit inventory</a><br>
      &nbsp;&nbsp;<a href="./delete-inventory.md">Delete inventory</a><br>
      &nbsp;&nbsp;<a href="./add-category.md">Add category</a><br>
      &nbsp;&nbsp;<a href="./edit-category.md">Edit category</a><br>
      &nbsp;&nbsp;<a href="./delete-category.md">Delete category</a><br>
      &nbsp;&nbsp;<a href="./add-supplier.md">Add supplier</a><br>
      &nbsp;&nbsp;<a href="./edit-suppplier.md">Edit supplier</a><br>
      &nbsp;&nbsp;<a href="./delete-supplier.md">Delete supplier</a><br>
      &nbsp;&nbsp;<a href="./create-inventory-report.md">Create Inventory Report</a><br><br>
      Finance Page<br>
      &nbsp;&nbsp;<a href="./create-report.md">Create Report</a><br>
      &nbsp;&nbsp;<a href="./create-audit">Create Audit</a><br><br>
      Accounts Page<br>
      &nbsp;&nbsp;<a href="./create-admin-account">Create Admin Account</a><br><br>
    </td>
    <td valign="top" >
      <h6> Accounts Page > Create Admin Account </h6>
        <img src = "./mock-ups/create-admin-account.png" />
      <h3>Create Admin Account</h3>
      <p>This serves as the means to create new admin accounts. <strong>Only accessible by CEO-level privilege</strong></p>
      <table border="1">
        <tr>
          <th>Use Case</th>
          <th>Create Admin Account</th>
        </tr>
        <tr>
          <td><b>Actors</b></td>
          <td>User (Primary), System (Secondary)</td>
        </tr>
        <tr>
          <td><b>Preconditions</b></td>
          <td>Current logged-in user must have CEO-level privilege</td>
        </tr>
        <tr>
          <td>Triggers</td>
          <td>User clicks the 'Create Account' button</td>
        </tr>
        <tr>
          <td><b>Basic Flow</b></td>
          <td>
            <ol>
              <li>User selects a picture for the account</li>
              <li>User enters the email, name, and password of the account to be created</li>
              <li>System validates credentials</li>
              <li>If valid, system creates the account and stores into account database</li>
            </ol>
          </td>
        </tr>
        <tr>
          <td><b>Alternative Flow</b></td>
          <td><strong>Invalid Credentials</strong>: System shows an error message<br>
          <strong>Email already used</strong>: System shows email already used error message
          </td>
        </tr>
        <tr>
          <td><b>Postconditions</b></td>
          <td>A new admin account is created and ready to use</td>
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
