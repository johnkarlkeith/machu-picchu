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
      <h6> Customer Page </h6>
        <img src = "./mock-ups/view-products.png" width='720' height='365'/>
      <h3>View Products</h3>
      <p>This page serves as a means to see the products currently available in the store</p>
      <table border="1">
        <tr>
          <th>Use Case</th>
          <th>Browse inventories</th>
        </tr>
        <tr>
          <td><b>Actors</b></td>
          <td>User (Primary), System (Secondary)</td>
        </tr>
        <tr>
          <td><b>Preconditions</b></td>
          <td>
          <ul>
              <li>Current user must be in the customer page (index)</li>
          </ul>
          </td>
        </tr>
        <tr>
          <td>Triggers</td>
          <td>None</td>
        </tr>
        <tr>
          <td><b>Basic Flow</b></td>
          <td>
            <ul>
                <li>User scrolls to view the available products of the honesty store</li>
            </ul>
          </td>
        </tr>
        <tr>
          <td><b>Alternative Flow</b></td>
          <td>
            <strong>User clicks on a product</strong>: A modal is shown that shows the product details such as price and description<br>
            <strong>User filters the products</strong>: Will filter the products displayed based on filters selected by the user 
          </td>
        </tr>
        <tr>
          <td><b>Postconditions</b></td>
          <td>
            None
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
