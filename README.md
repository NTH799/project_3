
Nicholas Hillis Project 3

1.
|        Graph file       |           MIS file           | Is an MIS? |
| ----------------------- | ---------------------------- | ---------- |
| small_edges.csv         | small_edges_MIS.csv          | Yes        |
| small_edges.csv         | small_edges_non_MIS.csv      | No         |
| line_100_edges.csv      | line_100_MIS_test_1.csv      | Yes        |
| line_100_edges.csv      | line_100_MIS_test_2.csv      | No         |
| twitter_10000_edges.csv | twitter_10000_MIS_test_1.csv | Yes        |
| twitter_10000_edges.csv | twitter_10000_MIS_test_2.csv | Yes        |

2.
|        Graph file       |  # of iterations |    Runtime  |
| ----------------------- |------------------|-------------|
| small_edges.csv         | 1                | 1s          |
| line_100_edges.csv      | 3                | 1s          |
| twitter_100_edges.csv   | 2                | 1s          |
| twitter_1000_edges.csv  | 3                | 1s          |
| twitter_10000_edges.csv | 4                | 3s          |

3.
a. For 3x4 cores:

runtime = 803s.
number of loops = 4
vertices after each iteration = 7018657, 36548, 392, 0


b. 
4x2 run time is about 1298s
2x2 run time was aborted as it had no output for over an hour

By using less cores, it took longer and longer for the program to finish

