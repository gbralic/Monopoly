# Monopoly
# Design Pattern & Software Development

The purpose of our project is to modelize a monopoly's game in C#.
In order to do that, we implemented a board by a linked list of a specific class named spaces (Propriety, special spaces). These classes inherit from the abstract class 'spaces'. We separated into these two classes because propriety can be bought by a player whereas special spaces can't be bought by a player.
We create several classes that inherit the class propriety : station, company, street. 

For the special spaces, we use a boolean attribut for identify the type of special spaces as Chance space, start, Luxe Tax, etc..) when we create an instance for each special space.



