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
      <h6> Products Page > Delete product </h6>
        <img src = "./mock-ups/delete-product.png" width='720' height='365'/>
      <h3>Delete Product</h3>
      <p>This modal serves as a means to delete products in the system.</p>
      <table border="1">
        <tr>
          <th>Use Case</th>
          <th>Delete Product</th>
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
                <li>Current user must be editing a product</li>
          </ul>
          </td>
        </tr>
        <tr>
          <td>Triggers</td>
          <td>User clicks the 'Delete Product' button when editing a product</td>
        </tr>
        <tr>
          <td><b>Basic Flow</b></td>
          <td>
            <ol>
              <li>User clicks the 'delete' button on the delete modal that pops up <br>
              upon clicking the 'delete product' button</li>
            </ol>
          </td>
        </tr>
        <tr>
          <td><b>Alternative Flow</b></td>
          <td>
            <strong>Product deletion aborted</strong>: Product will not be deleted and modal closes
          </td>
        </tr>
        <tr>
          <td><b>Postconditions</b></td>
          <td>
            The product will be soft deleted, meaning it will still be in <br>the system but will not be displayed 
          </td>
        </tr>
        <tr>
          <td><b>Exceptions</b></td>
          <td>Server is down → System will display an error message<br>
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
