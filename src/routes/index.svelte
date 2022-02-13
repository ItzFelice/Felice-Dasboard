<script> timetable = {
	Monday: [
  	{
    	name: "PH",
    	period: 1,
    	style: "",
  	},
  	{
    	name: "PM",
    	period: 1,
    	style: "",
  	},
  	{
    	name: "BI",
    	period: 2,
    	style: "",
  	},
  	{
    	name: "R",
    	period: 1,
    	style: "table-success",
  	},
  	{
    	name: "BM",
    	period: 2,
    	style: "",
  	},
  	{
    	name: "M3",
    	period: 2,
    	style: "",
  	},
  	{
    	name: "BC",
    	period: 2,
    	style: "",
  	},
	],
	Tuesday: [
  	{
    	name: "PJPK",
    	period: 1,
    	style: "",
  	},
  	{
    	name: "M3",
    	period: 2,
    	style: "",
  	},
  	{
    	name: "BI",
    	period: 1,
    	style: "",
  	},
  	{
    	name: "E",
    	period: 1,
    	style: "table-success",
  	},
  	{
    	name: "BM",
    	period: 2,
    	style: "",
  	},
  	{
    	name: "BC",
    	period: 3,
    	style: "",
  	},
  	{
    	name: "PJPK",
    	period: 1,
    	style: "",
  	},
	],
	Wednesday: [
  	{
    	name: "BC",
    	period: 3,
    	style: "",
  	},
  	{
    	name: "PM",
    	period: 1,
    	style: "",
  	},
  	{
    	name: "H",
    	period: 1,
    	style: "table-success",
  	},
  	{
    	name: "PKS",
    	period: 3,
    	style: "",
  	},
  	{
    	name: "BM",
    	period: 2,
    	style: "",
  	},
	],
	Thursday: [
  	{
    	name: "SA",
    	period: 1,
    	style: "",
  	},
  	{
    	name: "PJPK",
    	period: 1,
    	style: "",
  	},
  	{
    	name: "BM",
    	period: 2,
    	style: "",
  	},
  	{
    	name: "A",
    	period: 1,
    	style: "table-success",
  	},
  	{
    	name: "PM",
    	period: 1,
    	style: "",
  	},
  	{
    	name: "BC",
    	period: 2,
    	style: "",
  	},
  	{
    	name: "M3",
    	period: 2,
    	style: "",
  	},
	],
	Friday: [
  	{
    	name: "BI",
    	period: 2,
    	style: "",
  	},
  	{
    	name: "BM",
    	period: 2,
    	style: "",
  	},
  	{
    	name: "T",
    	period: 1,
    	style: "table-success",
  	},
  	{
    	name: "BC",
    	period: 2,
    	style: "",
  	},
  	{
    	name: "PM",
    	period: 1,
    	style: "",
  	},
  	{
    	name: "SA",
    	period: 2,
    	style: "",
  	},
	],
  };
</script>
<div class="container mt-5">
	<h1>My Dashboard</h1>
	<caption>School Timetable</caption>
<table class="table">
	<thead>
	  <tr  class="table-dark">
		<th scope="col">#</th>
		<th scope="col">1</th>
		<th scope="col">2</th>
		<th scope="col">3</th>
		<th scope="col">4</th>
		<th scope="col">-</th>
		<th scope="col">5</th>
		<th scope="col">6</th>
		<th scope="col">7</th>
		<th scope="col">8</th>
		<th scope="col">9</th>
		<th scope="col">10</th>
	  </tr>
	</thead>
	<tbody>
	  <tr>
		<th scope="row" class="table-dark" >MON</th>
		<td>Otto</td>{#each timetable.Monday as timeSlot, index}
		<td colspan={timeSlot.period} class={timeSlot.style}>
		  <button
			type="button"
			class="btn"
		  >
			{timeSlot.name}
		  </button>
		</td>
	  {/each}
	  </tr>
	  <tr>
		<th scope="row" class="table-dark">TUE</th>
		<td>Otto</td>{#each timetable.Tuesday as timeSlot, index}
		<td colspan={timeSlot.period} class={timeSlot.style}>
		  <button
			type="button"
			class="btn"
		  >
			{timeSlot.name}
		  </button>
		</td>
	  {/each}
	  </tr>
	  <tr>
		<th scope="row" class="table-dark">WED</th>
		<td>Otto</td>{#each timetable.Wednesday as timeSlot, index}
		<td colspan={timeSlot.period} class={timeSlot.style}>
		  <button
			type="button"
			class="btn"
		  >
			{timeSlot.name}
		  </button>
		</td>
	  {/each}
	  </tr>
	  <tr>
		<th scope="row" class="table-dark">THU</th>
		<td>Otto</td>{#each timetable.Thursday as timeSlot, index}
		<td colspan={timeSlot.period} class={timeSlot.style}>
		  <button
			type="button"
			class="btn"
		  >
			{timeSlot.name}
		  </button>
		</td>
	  {/each}
	  </tr>
	  <tr>
		<th scope="row" class="table-dark">FRI</th>
		<td>Otto</td>{#each timetable.Friday as timeSlot, index}
		<td colspan={timeSlot.period} class={timeSlot.style}>
		  <button
			type="button"
			class="btn"
		  >
			{timeSlot.name}
		  </button>
		</td>
	  {/each}>
	  </tr>
	  <tr>
	</tbody>
  </table>
</div>
<div class="text-center mt-5">
  <button type="button" class="btn btn-dark btn-sm">Log Out </button> 
 </div>