<body>
  <form action="">
    <table cellpadding="2" width="90%" align="center" cellspacing="2" bgcolor="grey">
      <tr>
        <th colspan="2">Railway Reservation Form</th>
      </tr>
      <tr>
        <td>From</td>
        <td><input type="text" /></td>
      </tr>
      <tr>
        <td>To</td>
        <td><input type="text" /></td>
      </tr>
      <tr>
        <td>Train no./Name</td>
        <td><input type="text" name="train" </td>
      </tr>
      <tr>
        <td>Select Class</td>
        <td>
          <select name="class">
            <option value="-1">Select</option>
            <option value="sleeper">Sleeper</option>
            <option value="AC IIIrd">3A</option>
            <option value="AC IInd">2A</option>
            <option value="AC Ist">1A</option>
          </select>
        </td>
      </tr>
      <tr>
        <td>No. of passengers</td>
        <td>
          <select name="passengers" id="">
            <option value="-1">Select</option>
            <option value="1">1 passenger</option>
            <option value="2">2 passengers</option>
            <option value="more">More than 2</option>
          </select>
        </td>
      </tr>
      <td>Passenger Name</td>
      <td>Age</td>
      <td>Gender</td>
      </tr>
      <tr>
        <td><input type="text" size"40"></td>
        <td><input type="text" size "2"></td>
        <td>
          <select name="gender" id="Gender">
            <option value="Male">Male</option>
            <option value="F">Female</option>
        </td>
        </select>
      </tr>
      <tr>
        <td><input type="text" size"40"></td>
        <td><input type="text" size "2"></td>
        <td>
          <select name="gender" id="Gender">
            <option value="Male">Male</option>
            <option value="F">Female</option>
        </td>
        </select>
      </tr>
      <tr>
        <td>Address</td>
        <td><input type="text" name"address" id="address" size="50"></td>
      </tr>
      <tr>
        <td>Payment Mode</td>
        <td><input type="radio">UPI
          <input type="radio">Credit/Debit Card
          <input type="radio">Netbanking
        </td>
      </tr>
      <tr>
        <td>Mobile no.</td>
        <td><input type="text" size="10"></td>
      </tr>
      <tr>
        <td><button>Reset</button></td>
        <td><button>Submit Form</button></td>
        <td><button>Cancel</button></td>
      </tr>
    </table>
  </form>
</body>
