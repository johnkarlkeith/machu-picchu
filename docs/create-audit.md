# Macchu Pichu

**Target:** TBD

---

<table>
  <tr>
    <td valign="top" style="width: 35%;">
      <h2>Site Map</h2>
      <a href="../readme.md">Revisions</a><br><br>
      Customer Page<br>
            &nbsp;&nbsp;<a href="./docs/viewproducts.md">View Products</a><br><br>     
      Admin Homepage<br>
      &nbsp;&nbsp;<a href="./sign-in.md">Sign in</a><br><br>
      Products Page<br>
      &nbsp;&nbsp;<a href="./add-product.md">Add product</a><br>
      &nbsp;&nbsp;<a href="./edit-product.md">Edit product</a><br>
      &nbsp;&nbsp;<a href="./delete-product.md">Delete product</a><br>
      &nbsp;&nbsp;<a href="./add-inventory.md">Add inventory</a><br>
      &nbsp;&nbsp;<a href="./browse-inventories.md">Browse inventories</a><br>
      &nbsp;&nbsp;<a href="./edit-inventory.md">Edit inventory</a><br>
      &nbsp;&nbsp;<a href="./delete-inventory.md">Delete inventory</a><br>
      &nbsp;&nbsp;<a href="./add-category.md">Add category</a><br>
      &nbsp;&nbsp;<a href="./edit-category.md">Edit category</a><br>
      &nbsp;&nbsp;<a href="./delete-category.md">Delete category</a><br>
      &nbsp;&nbsp;<a href="./add-supplier.md">Add supplier</a><br>
      &nbsp;&nbsp;<a href="./edit-supplier.md">Edit supplier</a><br>
      &nbsp;&nbsp;<a href="./delete-supplier.md">Delete supplier</a><br>
      &nbsp;&nbsp;<a href="./create-inventory-report.md">Create Inventory Report</a><br><br>
      Manage page<br>
      &nbsp;&nbsp;<a href="./create-report.md">Create Report</a><br>
      &nbsp;&nbsp;<a href="./create-audit.md">Create Audit</a><br><br>
      Manage Accounts Page<br>
      &nbsp;&nbsp;<a href="./create-admin-account.md">Create Admin Account</a><br><br>
    </td>
    <td valign="top" >
      <h6> Manage page > Create Audit </h6>
        <img src = "./mock-ups/create-audit.png" width='720' height='365'/>
      <h3>Create Audit</h3>
      <p>This serves to be the input for auditing the products in the Honesty Store.</p>
      <table border="1">
        <tr>
          <th>Use Case</th>
          <th>Create Audit</th>
        </tr>
        <tr>
          <td><b>Actors</b></td>
          <td>User (Primary), System (Secondary)</td>
        </tr>
        <tr>
          <td><b>Preconditions</b></td>
          <td><ul>
            <li>Current user must be logged in</li>
              <li>Current user must be in the Create Audit page</li>
          </ul>
          </td>
        </tr>
        <tr>
          <td>Triggers</td>
          <td>User clicks the 'Confirm Audit' button in the <br>audit confirmation modal </td>
        </tr>
        <tr>
          <td><b>Basic Flow</b></td>
          <td>
            <ol>
              <li>User enters the new quantity for each product</li>
              <li>User clicks the submit button</li>
              <li>User clicks 'Confirm Audit' button on the confirmation modal to <br>
              finalize the audit</li>
            </ol>
          </td>
        </tr>
        <tr>
          <td><b>Alternative Flow</b></td>
          <td>
            <strong>'Close' is clicked on confirmation modal</strong>: confirmation modal will be closed
          </td>
        </tr>
        <tr>
          <td><b>Postconditions</b></td>
          <td>
            A new audit will be created within the system and the latest inventories of <br> 
            audited products will be updated.  
          </td>
        </tr>
        <tr>
          <td><b>Exceptions</b></td>
          <td>Server is down → System will display an error message<br>
           Invalid form submission → System will highlight invalid fields<br>
           No values entered → 'Confirm Audit' button on cofirmation modal will not be visible
          </td>
        </tr>
        </table>
    </td>
  </tr>
</table>

---

<div align="center">
  © 2025 <a href="#">NexTech</a>
</div>
