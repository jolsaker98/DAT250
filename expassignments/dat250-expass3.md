# Report expass3

In particular, you should write about:

- Technical problems that you encountered during installation and use of MongoDB and how you resolved

- Screenshots for:

  - The correct validation of the installation package (https://docs.mongodb.com/manual/tutorial/verify-mongodb-packages/)

  - Relevant results obtained during Experiment 1 (it is not necessary to put a single screenshot on each substep, but at least one significant from each CRUD operation).

  - Experiment 2 example working and the additional Map-reduce operation (and its result) developed by each of you.

- Reason about why your implemented Map-reduce operation in Experiment 2 is useful and interpret the collection obtained.

- Any pending issues with this assignment which you did not manage to solve

## Technical problems encountered

No spesific problems encountered during the installation and use of MongoDB

## Screenshots

<details>
<summary><b>SHA-256 checksum</b></summary>
<img width="897" alt="SHA-256_checksum" src="https://user-images.githubusercontent.com/111968598/191615611-f22bf729-3f75-4519-8630-62f9c2069d35.png">
</details>

<details>
<summary><b>Experiment 1 insert-document</b></summary>
<img width="350" alt="Experiment 1 insert-document" src="https://user-images.githubusercontent.com/111968598/191616753-ddc2c26f-6894-468e-b988-e1012b7f5658.png">
</details>


<details>
<summary><b>Experiment 1 query-document</b></summary>
<img width="397" alt="Experiment 1 query-document" src="https://user-images.githubusercontent.com/111968598/191616787-1119f383-b2d8-4d7b-9092-4f9b24f76a24.png">
</details>

<details>
<summary><b>Experiment 1 query-nested-document</b></summary>
<img width="594" alt="Experiment 1 query-nested-document" src="https://user-images.githubusercontent.com/111968598/191616824-c8d750bc-75eb-4def-a157-a363dbc2c7c9.png">
</details>

<details>
<summary><b>Experiment 1 query-array-document</b></summary>
<img width="541" alt="Experiment 1 query-array-document" src="https://user-images.githubusercontent.com/111968598/191616863-b0745947-b718-4a1b-b0d7-e1c3f2d9bb19.png">
</details>

<details>
<summary><b>Experiment 1 query-return-field</b></summary>
<img width="658" alt="Experiment 1 query-return-field" src="https://user-images.githubusercontent.com/111968598/191616896-0fe6264e-7087-4f8d-8bc2-30ca1a311af4.png">
</details>

<details>
<summary><b>Experiment 1 query-null</b></summary>
<img width="435" alt="Experiment 1 query-null" src="https://user-images.githubusercontent.com/111968598/191616987-94bed7fb-7cef-4c11-98d8-ab4c1952664b.png">
</details>

<details>
<summary><b>Experiment 1 update-document</b></summary>
<img width="1440" alt="Experiment 1 update-document" src="https://user-images.githubusercontent.com/111968598/191616938-a5280a4b-3e82-43cb-9d8c-8957a8d8bc6d.png">
</details>

<details>
<summary><b>Experiment 1 update-aggregation exp 1</b></summary>
<img width="394" alt="Experiment 1 update-aggregation exp 1" src="https://user-images.githubusercontent.com/111968598/191617049-5cd20cd0-a357-433e-8965-3c4c40a9629f.png">
</details>

<details>
<summary><b>Experiment 1 update-aggregation exp 2</b></summary>
<img width="395" alt="Experiment 1 update-aggregation exp 2" src="https://user-images.githubusercontent.com/111968598/191617088-819e2b7d-5127-41c9-9ba6-b415bad4a715.png">
</details>

<details>
<summary><b>Experiment 1 update-aggregation exp 3</b></summary>
<img width="379" alt="Experiment 1 update-aggregation exp 3" src="https://user-images.githubusercontent.com/111968598/191617122-ee43561d-d2cd-4171-b76d-ebbd1a03ed85.png">
</details>

<details>
<summary><b>Experiment 1 update-aggregation exp 4</b></summary>
<img width="568" alt="Experiment 1 update-aggregation exp 4" src="https://user-images.githubusercontent.com/111968598/191617173-b7fd5f3a-6805-4e24-860d-01f9e9b09121.png">
</details>

<details>
<summary><b>Experiment 1 update-aggregation exp 5</b></summary>
<img width="536" alt="Experiment 1 update-aggregation exp 5" src="https://user-images.githubusercontent.com/111968598/191617217-46390ab8-ec04-4a9f-8f71-15ac20d39f48.png">
</details>

<details>
<summary><b>Experiment 1 remove-document</b></summary>
<img width="660" alt="Experiment 1 remove-document" src="https://user-images.githubusercontent.com/111968598/191617264-cdd85fa6-0990-4d2f-9dd9-da5ebccce64f.png">
</details>

<details>
<summary><b>Experiment 1 bulk-write</b></summary>
<img width="682" alt="Experiment 1 bulk-write" src="https://user-images.githubusercontent.com/111968598/191617304-5db3d869-58ec-4141-ac0e-c7b7fb818243.png">
</details>

<details>
<summary><b>Experiment 2 price-per-customer</b></summary>
<img width="638" alt="Experiment 2 price-per-customer" src="https://user-images.githubusercontent.com/111968598/191617330-f2858cfe-1c4b-4fdb-8aa1-7f94d058137c.png">
</details>

<details>
<summary><b>Experiment 2 count-quantity-average</b></summary>
<img width="486" alt="Experiment 2 count-quantity-average" src="https://user-images.githubusercontent.com/111968598/191617360-532d9cfc-0075-43a5-93a0-831ea97a5bac.png">
</details>

## Own implementation of Map-reduce operation

In my implementation below, I get a calculation sum of all quantity of products sold for the specific dates. We can then look at the best day with the most sales. The collection shows the date and quantity values. 

<details>
<summary><b>Experiment 2 own execution</b></summary>
<img width="531" alt="Screen Shot 2022-09-22 at 12 02 16 AM" src="https://user-images.githubusercontent.com/111968598/191618484-da0f18e4-4fd1-4bed-ba7d-f810f0dfd908.png">
</details>

## Pending issues

No pending issues after assignment was done
