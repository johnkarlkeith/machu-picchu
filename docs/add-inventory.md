# Macchu Pichu

**Target:** TBD

---

<table>
  <tr>
    <td valign="top" style="width: 35%;">
      <h2>Site Map</h2>
      <a href="../readme.md">Revisions</a><br><br>
      Customer Page<br>
      &nbsp;&nbsp;<a href="./view-products.md">View Products</a><br><br>     
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
      <h6> Products Page > Add inventory </h6>
        <img src = "./mock-ups/add-inventory.png" width='720' height='365'/>
      <h3>Add inventory</h3>
      <p>This modal serves as a means to add an inventory to a product in the system.</p>
      <table border="1">
        <tr>
          <th>Use Case</th>
          <th>Add inventory</th>
        </tr>
        <tr>
          <td><b>Actors</b></td>
          <td>User (Primary), System (Secondary)</td>
        </tr>
        <tr>
          <td><b>Preconditions</b></td>
          <td><ul>
              <li>Current user must be logged in</li>
                <li>Current user must be in the products page</li>
          </ul>
          </td>
        </tr>
        <tr>
          <td>Triggers</td>
          <td>User clicks the box icon button at the bottom right of a product in the product page</td>
        </tr>
        <tr>
          <td><b>Basic Flow</b></td>
          <td>
            <ol>
              <li>User queries the database for existing suppliers in the database and select a<br> query result from the dropdown that appears</li>
              <li>User will set the price of the inventory of the product by <br>entering the wholesale price and doing one of the following</li>
                <ul>
                    <li>Setting profit margin manually, retail price is calculated automatically</li>
                    <li>Setting retail price manually, profit margin is calculated automatically</li>
                    <li>Autocalculating retrail price with a profit margin default value of 10%</li>
                </ul>
                <li>User fills in the total units and expiration date fields</li>
                <li> <strong>(optional)</strong> User sets a description for the inventory</li>
            </ol>
          </td>
        </tr>
        <tr>
          <td><b>Alternative Flow</b></td>
          <td>
            <strong>Form submitted with empty description field</strong>: Inventory will be created<br> but the description field will be empty in the database
          </td>
        </tr>
        <tr>
          <td><b>Postconditions</b></td>
          <td>
            The inventory will be created in the database 
          </td>
        </tr>
        <tr>
          <td><b>Exceptions</b></td>
          <td>Server is down → System will display an error message<br>
          Submitting with missing required fields → System will highlight missing required<br> fields
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
