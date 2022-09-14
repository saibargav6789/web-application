Index.html
<!DOCTYPE html>
<html lang=”en”>
  <head>
    <meta charset=”UTF-8” />
    <meta http-equiv=”X-UA-Compatible” content=”IE=edge” />
    <meta name=”viewport” content=”width=device-width, initial-scale=1.0” />
    <title>Registration Form</title>
    <link rel=”stylesheet” href=”style.css” />
    <script src=”script1.js” defer></script>
    <style>
   {
        Margin: 0;
        Padding: 0;
        Box-sizing: border-box;
        Font-family: “Segoe UI”, Tahoma, Geneva, Verdana, sans-serif;
      }
      Body {
        Background-color:rgb(15, 110, 199);
      }
      .head {
        Margin-top: 1rem;
        /* color: white; */
      }
      .box {
        Display: flex;
        Align-items: center;
        Justify-content: center;
        Margin-top: 3rem;
      }
      .form {
        Display: flex;
        Align-items: center;
        Flex-direction: column;
        Background-color: white;
        Width: 600px;
        Height: 500px;
        Box-shadow: 2px 4px 10px gray;
        Border: 1px solid black;
        Border-radius: 20px;
        Padding: 20px;
      }
      .input {
        Padding: 10px 15px;
        Border: 2px solid rgba(0, 0, 0, 0.4);
        Font-size: 18px;
        Outline: none;
        Border-radius: 10px;
        Background-color: rgba(0, 0, 0, 0.02);
      }
      Label {
        Font-size: 18px;
        Letter-spacing: 1.4px;
      }
      .tableForm {
        Margin-top: 10px;
      }
      .btn {
        Background-color: rgb(66, 55, 231);
        Color: white;
        Padding: 10px 20px;
        Font-size: large;
        Font-weight: 600;
        Border-radius: 10px;
      }

      Input:invalid:focus {
        Border: 2px solid red;
      }

      .table {
        Border: 2px solid black;
        Margin: 40px auto;
      }

      .td,
      .th {
        Padding: 10px;
        Text-align: center;
      }

      .subHead {
        Text-align: center;
        Margin-top: 2rem;
      }
    </style>
  </head>
  <body>
    <h1 align=”center” class=”head”>WD101 – Level 8</h1>
    <div class=”box”>
      <form class=”form” id=”form”>
        <h2 align=”center”>Registration Form</h2>

        <table class=”tableForm” cellspacing=”25px”>
          <tr>
            <td><label for=”name”>Name :</label></td>
            <td>
              <input
                Class=”input”
                Type=”text”
                Name=”name”
                Id=”name”
                Placeholder=”Full Name”
                Required
              />
            </td>
          </tr>
          <tr>
            <td><label for=”email”>E-mail :</label></td>
            <td>
              <input
                Class=”input”
                Type=”email”
                Name=”email”
                Id=”email”
                Placeholder=”Email”
                Required
              />
            </td>
          </tr>
          <tr>
            <td><label for=”name”>Password :</label></td>
            <td>
              <input
                Class=”input”
                Type=”password”
                Name=”password”
                Id=”password”
                Placeholder=”Password”
                Required
              />
            </td>
          </tr>
          <tr>
            <td><label for=”dob”>Date Of Birth :</label></td>
            <td>
              <input
                Style=”width: 220px”
                Class=”input”
                Type=”date”
                Name=”dob”
                Id=”dob”
                Required
              />
            </td>
          </tr>
          <tr>
            <td colspan=”2”>
              <input type=”checkbox” name=”agree” id=”agree” />
              <label for=”checkbox”>Accept Terms & Conditions</label>
            </td>
          </tr>
          <tr>
            <td>
              <button class=”btn” type=”submit”>Submit</button>
            </td>
          </tr>
        </table>
      </form>
    </div>

    <div class=”entry”>
      <h2 class=”subHead”>Entries</h2>
      <div id=”tableDiv”></div>
    </div>
  </body>
</html>
