#edns310  #design 


## Original Equations

| Variable                    | Type     | Units      | Equation                                      |
| --------------------------- | -------- | ---------- | --------------------------------------------- |
| Planting                    | Flow     | Trees/year | 10                                            |
| Saplings                    | Stock    | Trees      | Integ(Planting-Maturing), initial value = 500 |
| Time for saplings to mature | Constant | Years      | 50                                            |
| Maturing                    | Flow     | Trees/year | Saplings/Time for saplings to mature          |
| Mature trees                | Stock    | Trees      | Integ(Maturing-Harvesting), Initial value 500 |
| Harvesting                  | Flow     | Trees/year | 10                                            |
#### Stock In/Outflows
- Flows for Saplings:
	- Inflows: Planting
	- Outflows: Maturing
- Flows for Mature Trees:
	- Inflows: Maturing
	- Outflows: Harvesting
### Stock and Flow Diagram
![[Screenshot 2025-12-16 at 5.30.07 PM.png]]

## Part D (Graphs)
![[Screenshot 2025-12-16 at 5.33.13 PM.png]]
![[Screenshot 2025-12-16 at 5.33.23 PM.png]]
- Results are as expected - checking the math over by hand, maturing should start out at 10 (500/10), which means that inflows and outflows on both stocks equal each other, meaning that neither of the stocks should be moving.
---

## Updated Equations (Part E)
| Variable                    | Type     | Units      | Equation                                      |
| --------------------------- | -------- | ---------- | --------------------------------------------- |
| Planting                    | Flow     | Trees/year | 15                                            |
| Saplings                    | Stock    | Trees      | Integ(Planting-Maturing), initial value = 500 |
| Time for saplings to mature | Constant | Years      | 50                                            |
| Maturing                    | Flow     | Trees/year | Saplings/Time for saplings to mature          |
| Mature trees                | Stock    | Trees      | Integ(Maturing-Harvesting), Initial value 500 |
| Harvesting                  | Flow     | Trees/year | 15                                            |
![[Screenshot 2025-12-16 at 5.36.58 PM.png]]
![[Screenshot 2025-12-16 at 5.37.05 PM.png]]
- Changing the planting/harvesting values made saplings increase over time and mature trees decrease over time. This makes sense compared to the previous scenario where values happened to line up, which is an important lesson to take (I'm doing this late and after having already considered this, but) of that just because something isn't changing or not behaving as you may have initially expected, doesn't mean your model is nonfunctional - neither stock moving was an instance of math happening to line up, not a sign that equations weren't working. Beyond that, noting that changing constants can lead to significant changes in graphs - you may not initially expect that changing those constants would affect the degree of the graph (constant vs exponential), but emergent behaviors like that are pretty common, especially as S&F diagrams get more complicated.