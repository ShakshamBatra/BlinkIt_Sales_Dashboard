This Project involves analyzing sales Data using DAX queries in PowerBi to uncover key insights and trends.The Dashboard provides a comprehensive view of sales performance, helping stakeholders make data-driven
decisions.
DAX queries that are used in this:
New Parameter was used to enchance the Dashboard
Metrix = {
    ("Total Sales", NAMEOF('BlinkIT Grocery Data'[Total Sales]), 0),
    ("Avg Sales", NAMEOF('BlinkIT Grocery Data'[Avg Sales]), 1),
    ("No. of Items", NAMEOF('BlinkIT Grocery Data'[No. of Rows]), 2),
    ("Avg Rating", NAMEOF('BlinkIT Grocery Data'[Avg Rating]), 3)
}
