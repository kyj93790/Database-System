Goal : The goal of this projet is to provide a realistic experience in the conceptual design, logical design, implementation, operation, and maintenance of a realational database and associated applications.


General Motors, Ford, Toyota, Volkswagen과 같은 자동차 회사의 데이터 베이스를 구축.
Relational Schema를 설계하고, 이를 바탕으로 Physical Schema Diagram 작성.
다양한 Query문에 맞게 데이터를 추출가능한 코드를 MySQL을 통해 작성.


vehicles	: Each vehicles as a vehicle indentification number (VIN).

brands		: Each company may have several brands.

models		: Each brand offers several models. Each model may com in a variety of body styles (4-door, wagen, etc.)

options		: Color, engine, transmission

suppliers	: Suppliers supply certain parts of certain models.

company-owned manufacturing plants	: Some plants supply certain parts for certain models; others do final assembly of actual cars.

customers	: Stick to name, address, phone, gender, and annual income for individual buyers. The costomer may also be a company.
