# Rohith Reddy Kondle

### Favourite Place is Goa

Goa is located in south **India** and is famous for wonderful **beaches** with good tourism facilities

***

## Travel Plan
1. Travel to Kansas City Airport (MCI)
   1. Take a flight from MCI to Chicago
   2. Then Onboard a flight from Chicago to New Delhi, India
   3. Then take Domestic flight from New Delhi to Goa Airport
2. Book a cab from airport to the port area
3. Reached the destination


## List of items to bring
* Camping tents
* Grill Chicken
* Drinks:
  * Mocktails
  * Beers
* Beach wears 
* Trekking set

[Quick link for AboutMe](AboutMe.md)

---

## Try these Delicious items:

Try these Four Delicious Food items which are listed below

| Food/drink item | location | Expected Price |
| --- | --- | --- |
| Chicken Biryani | Hyderabad | Rs 500 |
| Fish | Vizag | Rs 1000 |
| Bamboo Chicken | lambasinghi | Rs 450 |
| prawns | vijayawada | Rs 900 |

---

## Pithy Quotes

> "Arise,awake and donot stop until the goal is reached." -*Swami Vivekananda*<Br>
> "Truth can be stated in a thousand different ways, yet each one can be true." -*Swami Vivekananda*

---

## Depth First Search

>Depth-first search (DFS) is an algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking.

[Click Here to Know More](https://en.wikipedia.org/wiki/Depth-first_search#:~:text=Depth%2Dfirst%20search%20(DFS),along%20each%20branch%20before%20backtracking.)

```
vector<vector<int>> adj; // graph represented as an adjacency list
int n; // number of vertices

vector<bool> visited;

void dfs(int v) {
    visited[v] = true;
    for (int u : adj[v]) {
        if (!visited[u])
            dfs(u);
    }
}
```
[Code Source](https://cp-algorithms.com/graph/depth-first-search.html)