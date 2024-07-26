# UK-TRAIN-RIDES

### create tables in postgre sql

CREATE TABLE tr(
	Transaction_ID VARCHAR,
    Date_of_Purchase DATE,
	Time_of_Purchase TIME,
	Purchase_Type TEXT,
	Payment_Method TEXT,
	Railcard TEXT,
	Ticket_Class TEXT,
	Ticket_Type TEXT,
	Price INT,
	Departure_Station TEXT,
	Arrival_Destination TEXT,
	Date_of_Journey DATE,
	Departure_Time TIME,
	Arrival_Time TIME,
	Actual_Arrival_Time TIME,
	Journey_Status TEXT,
	Reason_for_Delay TEXT,
	Refund_Request TEXT
)
