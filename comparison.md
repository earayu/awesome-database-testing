* database (generation)
* sql (generation)
* performance (testing)
* differential (testing)
* integrity (testing)
* mutation (testing)

| Tool      | Scope              | Method       | Year | Pub*   | Author      |
|:----------|:-------------------|:-------------|:-----|:-------|:------------|
| N/A       | database           | parallel     | 94   | SIGMOD | Bell Lab    |
| N/A       | sql                | stochastic   | 98   | VLDB   | Microsoft   |
| N/A       | performance        | template     | 04   | VLDB   | Oracle      |
| N/A       | database           | stochastic   | 05   | VLDB   | Microsoft   |
| N/A       | sql/coverage       | genetic      | 07   | VLDB   | Microsoft   |
| RQP       | functionality      | constraints  | 07   | ICDE   | ETH Zurich  |
| QAGen     | database           | constraints  | 07   | SIGMOD | ETH Zurich  |
| ADUSA     | verification       | constraints  | 08   | ASE    | UT Austin   |
| Qex       | database           | constraints  | 09   | LPAR   | Microsoft   |
| N/A       | sql/execution      | differential | 09   | SIGMOD | Microsoft   |
| ??        | verification       | ??           | 10   | POPL   | Harvard     |
| N/A       | predicate/mutation | constraints  | 10   | STVR   | Oviedo      |
| CorrectDB | authentication     | ??           | 13   | VLDB   | Stony Brook |
| N/A       | database/mutation  | constraints  | 15   | VLDB   | IIT         |
| N/A       | integrity          | mutation     | 15   | TOSEM  | Sheffield   |
| EvoSQL    | sql                | search       | 18   | ICSE   | Delft       |
| Apollo    | performance        | differential | 19   | VLDB   | Geogia Tech |


Unclassified (no suitable catrgory):
| Tool | Scope        | Method | Year | Pub*    | Author |
|:-----|:-------------|:-------|:-----|:--------|:-------|
| N/A  | sql/coverage | ???    | 04   | SIGSOFT | Oviedo |



Necessary background to understand the research:
* DBMS structure
* Query processing (non-deterministic)
* Real-world requirement: data distribution, performance, correctness.
* Automated testing: method, challenges, current approach
