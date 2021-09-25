```ghkerin
User Story #1

As a sales agent
I want to query for the availability and location of a part
So that I can make a sale to a customer

	Scenario 1.1:

		Angie (sales agent) gets a call from Johnny (buyer), one of her best clients.
		He needs a single piece of “widget A” for a plane that just failed inspection.
		If Johnny cannot get this piece then the airline will not have the capacity
		to fly all their passengers.

		Angie quickly queries for “widget A” and discovers that she has “1000” of them
		in her warehouse.

		Johnny says to have 10 of them delived by overnight mail to his hanger at the
		airport.

		Angie does not bother collecting payment information since their business
		already has a relationship with the client. She just places the order and
		makes sure she classifies it as a high priority order. She trusts that
		the warehouse team will do their job in deliving the widget. She trusts that
		the accounting team will do their job in handling billing.

	Scenario 1.2:

		Angie (sales agent) gets a call from Johnny (buyer), one of her best clients.
		He needs a single piece of “widget A” for a plane that just failed inspection.
		If Johnny cannot get this piece then the airline will not have the capacity
		to fly all their passengers.

		Angie quickly queries for “widget A” and discovers that they do not have any
		of those widgets in their warehouse.

		She tells Johnny that they cannot help him, and ends the call.
		Angie then puts a note into the system to tell the purchasing agents about the
		fact that she could not make a sale because they did not have the inventory
		available.
```

```ghkerin
User Story #2:

As a purchasing manager
I want to know when my warehouse is in danger of not being able to hold incomming inventory
So that I can dump inventory before the new inventory arrives
```

```ghkerin
User Story #3:

As a purchasing manager
I want to know what inventory items I should dump
So that I can make room for more inventory
```

```ghkerin
User Story #4:

As a warehouse worker
I want inventory movement to automatically be updated in our system of record
So that nobody has to do data entry

	Scenario: 4.1
		Jack (warehouse worker)goes into a truck and starts transfering pallets. For each
		pallet, he scans the contents to determine what it is and where it should go.
		He confirms the information and proceeds to move the contents.
		When he finally transfers the pallet, the system informs him that it knows
		that the contents have been delivered. Jake simply confirms that fact.
```

```ghkerin
User Story #5:

As a purchasing agent
I want to buy new inventory
So that we can support our sales team in selling

	Scenario 5.1:
		Sarah (purchasing agent) receives a message from Angie (sales agent) that
		said she was not able to make a sale of “widget A” because her report told
		her that they did not have any in stock.
		Sarah determines that she want to buy some of those widget’s from her vendor
		because she believes that more clients will make the same request.
		She places the order, and signals to the warehouse team that they should
		expect some new inventory. That report will also contain where the inventory
		should be placed in the warehouse for maximum efficiency.
```

```ghkerin
User Story #6:

As a warehouse worker
I want to know where to put inventory when it arrives
So that I do not have conflicts with other warehouse workers about location

	Scenario 6.1:
		Jack (warehouse worker) is watching a truck pull into the warehouse. He knows
		the contents in the truck, based on a report that he received from the
		purchasing department. He also know where in the warehouse he should transfer
		each pallet in the truck because that is also part of the report.
```

```ghkerin
User Story #7:

As a purchasing manager
I want to have a historical record of what inventory was located at a particular location at a particular time
So that I can potentially do statistical analysis
```

```ghkerin
User Story #8:

As a purchasing manager
I want to have a historical record of where a particular inventory item was throughout its lifetime
So that I can potentially do statistical analysis
```

```ghkerin
User Story #9

As a warehouse worker
I want to give a pallet to a robot 
So that I can avoid doing it myself

    Scenario 9.1:

    Jake (warehouse worker) is informed from his app that there are 100 widgets of type "A".
    Type A widgets are transferrable by the drones.

    When Jake takes the pallet out of the truck, he points his device at the drone and informs
    the drone where to put the pallet. He uses the app to find a open spot that is not reserved
    for anything (location 100) and chooses that location.

    When the drone moves away he recieves a notice 5 minutes later that the drone has placed 
    the pallet at location 100.
```