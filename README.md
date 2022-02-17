
<!-- Modal Header -->
<div class="modal fade" id="myModal" tabindex="-1" role="dialog" data-target="myModal" data-id="booking" aria-labelledby="myModalCenterTitle" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="myModalCenterTitle">Add Booking</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">×</span>
        </button>
      </div>

<!-- Modal Body -->
      <div class="modal-body">
	  <form id="FormEditUser">
	        <div class="form-group">
				<label for="user_id">Booking ID</label>
				<input autocomplete="off" spellcheck="false" autocorrect="off" id="user_id" name="user_id" data-id="user_id" class="form-control" type="text" required readonly>
			</div>
			<div class="form-group">
				<label for="fullname">Full Name</label>
				<input type="text" id="fullname" name="fullname" required="" class="form-control ">
			</div>
			<div class="form-group">
				<label for="phonenumber">Phone Number</label>
				<div class="input-group">
					<span class="input-group-text p-0 bg-white">
						<select id="phonecode" name="phonecode" class="form-control border-0" required>
					    <option value="86">86</option>
					    <option value="852">852</option>
					    <option value="91">91</option>
					    <option value="62">62</option>
					    <option value="81">81</option>
					    <option value="82">82</option>
						<option value="60">60</option>
					    <option value="65">65</option>
					    <option value="66">66</option>
				        </select>
					</span>
					<input type="tel" id="phonenumber" name="phonenumber" required="" class="form-control ">
				</div>
			</div>
			<div class="form-group">
				<label for="date">Date</label>
				<input type="date" id="date" name="date" required="" class="form-control">
			</div>
			<div class="form-group">
				<label for="time">Time Start</label>
				<input type="time" id="time_start" name="time_start" required="" class="form-control">
			</div>
			<div class="form-group ">
				<label for="duration">Duration</label>
				<select id="duration" name="duration" class="form-control" required>
					<option selected disabled>Select an option</option>
					<option value="30">00 hours 30 mins</option>
					<option value="60">01 hours 00 mins</option>
					<option value="90">01 hours 30 mins</option>
					<option value="120">02 hours 00 mins</option>
					<option value="150">02 hours 30 mins</option>
					<option value="180">03 hours 00 mins</option>
				</select>
			</div>
			<div class="form-group ">
				<label for="court">Court</label>
				<select id="court" name="court" value="court" class="form-control" required>
					<option selected disabled>Select an option</option>
					<option value="Court 1">Court 1</option>
					<option value="Court 2">Court 2</option>
					<option value="Court 3">Court 3</option>
					<option value="Court 4">Court 4</option>
					<option value="Court 5">Court 5</option>
					<option value="Court 6">Court 6</option>
					<option value="Court 7">Court 7</option>
				</select>
			</div>
			<div class="form-group ">
				<label for="user_status">Status</label>
				<select id="user_status" name="user_status" class="form-control" required>
					<option selected disabled>Select an option</option>
					<option value="Pending">Pending</option>
					<option value="Active">Active</option>
					<option value="Approved">Approved</option>
					<option value="Rejected">Rejected</option>
					<option value="Cancelled">Cancelled</option>
				</select>
			</div>
			<div class="form-group ">
				<label for="pricetype">Price Type</label>
				<select id="pricetype" name="pricetype" class="form-control" required>
					<option selected disabled>Select an option</option>
					<option value="Normal">Normal</option>
					<option value="Student-Collage">Student-Collage</option>
					<option value="Student-Secondary">Student-Secondary</option>
					<option value="Student-Primary">Student-Primary</option>
				</select>
			</div>
			<div class="form-group">
			   <p>Type</p>
	               <label class="container">Standby
				   <input type="radio" checked="checked" value="standby" name="type">
                   <span class="checkmark"></span>
                </label>
                   <label class="container">Reconfirmed
				   <input type="radio" value="reconfirmed" name="type">
                   <span class="checkmark"></span>
                </label>
				</label>
                   <label class="container">Cancelled
				   <input type="radio" value="cancelled" name="type">
                   <span class="checkmark"></span>
                </label>
				</label>
                   <label class="container">Cancelled(Absent)
				   <input type="radio" value="cancelled(absent)" name="type">
                   <span class="checkmark"></span>
                </label>
			</div>
			<div class="form-group">
			    <p>Payment</p>
	               <label class="container">Paid
				   <input type="radio" checked="checked" value="paid" name="payment">
                   <span class="checkmark"></span>
                </label>
                   <label class="container">Unpaid
				   <input type="radio" value="unpaid"name="payment">
                   <span class="checkmark"></span>
                </label>
			</div>
			<div class="form-group ">
				<label for="amount">Actual Amount (RM)</label>&nbsp;&nbsp;
				<input type="text" name="amount" id="amount" /><br><br>
			<div>

<!-- Modal Footer -->
      <div class="modal-footer">
	    <button type="submit" class="btn btn-primary">Submit</button>
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
        
      </div>
    </div>
  </div>
</div>
