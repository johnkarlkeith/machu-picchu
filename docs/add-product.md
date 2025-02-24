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
      &nbsp;&nbsp;<a href="./add-product.md">Add product</a><br>
      &nbsp;&nbsp;<a href="./edit-product.md">Edit product</a><br>
      &nbsp;&nbsp;<a href="./delete-product.md">Delete product</a><br>
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
      Manage Accounts Page<br>
      &nbsp;&nbsp;<a href="./create-admin-account">Create Admin Account</a><br><br>
    </td>
    <td valign="top" >
      <h6> Products Page > Add product </h6>
        <img src = "./mock-ups/add-product.png" />
      <h3>Create Admin Account</h3>
      <p>This modal serves as a means to create new products in the system.</p>
      <table border="1">
        <tr>
          <th>Use Case</th>
          <th>Add product</th>
        </tr>
        <tr>
          <td><b>Actors</b></td>
          <td>User (Primary), System (Secondary)</td>
        </tr>
        <tr>
          <td><b>Preconditions</b></td>
          <td>Current user must be logged in<br>
            Current user must be in the products page
          </td>
        </tr>
        <tr>
          <td>Triggers</td>
          <td>User clicks the 'Add product' button</td>
        </tr>
        <tr>
          <td><b>Basic Flow</b></td>
          <td>
            <ol>
              <li>User enters in the product name</li>
              <li>User queries for existing categories and clicks on a result from a dropdown to select it</li>
              <li>User selects a product image</li>
              <li>User fills in other optional fields</li>
              <li>User may opt to set the 'reorder point' field manually by checking the 'set manual reorder point' checkbox. This will make the 'reorder point' field required</li>
            </ol>
          </td>
        </tr>
        <tr>
          <td><b>Alternative Flow</b></td>
          <td>
            <strong>Form submitted with empty optional fields</strong>: Product will be created but with empty optional fields in data
          </td>
        </tr>
        <tr>
          <td><b>Postconditions</b></td>
          <td>
            A new product will be created and ready to use in the products page
          </td>
        </tr>
        <tr>
          <td><b>Exceptions</b></td>
          <td>Server is down → System will display an error message<br>
           Incomplete form submission → System will highlight missing required fields
          </td>
        </tr>
        </table>
        <table>
        <tr>
          <th>Use Case</th>
          <th>Upload product image</th>
        </tr>
        <tr>
          <td><b>Actors</b></td>
          <td>User</td>
        </tr>
        <tr>
          <td><b>Preconditions</b></td>
          <td>
            <ul>
              <li>User is on the Products page</li>
              <li>User has access to an image file on their device</li>
            </ul>
          </td>
        </tr>
        <tr>
          <td>Triggers</td>
          <td>User clicks the 'Select a picture' button</td>
        </tr>
        <tr>
          <td><b>Basic Flow</b></td>
          <td>
            <ol>
              <li>User clicks on 'Select a picture' button</li>
              <li>User selects an image from the system file selection dialog</li>
              <li>System displays the image in admin account creation form</li>
            </ol>
          </td>
        </tr>
        <tr>
          <td><b>Alternative Flow</b></td>
          <td><strong>Image selection aborted</strong>: No image is selected, no changes will be observed<br>
          </td>
        </tr>
        <tr>
          <td><b>Postconditions</b></td>
          <td>Image is now displayed on admin product creation form</td>
        </tr>
        <tr>
          <td><b>Exceptions</b></td>
          <td>Selected file is not an image → System shows error message</td>
        </tr>
        </table>
    </td>
  </tr>
</table>

---

<div align="center">
  © 2025 <a href="#">NexTech</a>
</div>
