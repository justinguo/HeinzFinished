<p> Change to MongoDB schema </p>
<p>
	<li> add "shopping cart" field to "user" collection </li>
		<ul> a book arrary: keeping track of all the books </ul>
			<ul> every book item in this array has an additional field "qty": represent the quantity in the cart </ul>
        <ul> amount: keeping track of total amount in the shopping cart </ul>
        <ul> items: keeping track of all items in the shopping cart </ul>
	<li> add "history cart" field to "user" collection </li>
		<ul> a book array that simply keeps track all the books that a user has purchased successfully </ul>
