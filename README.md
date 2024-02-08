# Point Location in Two-Dimensional Space Using Separator Method

## Description

This project is developed as an educational tool to teach and demonstrate the algorithm for locating a point in a two-dimensional space using the separator method. The algorithm determines in which polygonal subdivision element a given point P on the plane is located.

## Technologies

- Programming language: *Python 3.9*
- Graphics libraries: *[Environment prepared by BIT](https://github.com/aghbit/Algorytmy-Geometryczne)*
- Development environment: *Jupyter Notebook*

## Features

- Loading a region with a polygonal subdivision from a user interface.
- Entering the point P by the user.
- Graphical presentation of the algorithm's steps:
  - Showing the space division.
  - Highlighting point P and tracking the localization path within the structure.
- Visualization of the result – indicating the element containing point P.

## How to Run?

1. Clone the repository
2. Install required dependencies *requirements.txt*
3. You can either use one of our premade polygon divisions saved in *raw.py*. Should you want to use your own one, add it to the file, please follow the [definition](#regular-subdivision-definition)
4. Follow [usage examples](#usage-examples)

### Regular Subdivision Definition

Let the set of vertices in the subdivision form an ordered sequence with respect to the y-coordinate (in case of equal values, with respect to the x-coordinate).

A vertex \(v_k\) is considered regular if there exist edges \( (v_i,v_k) \) and \( (v_k,v_j) \) for \(i < k < j\). A subdivision is regular if all vertices in the sequence, except for the first and last, are regular.


## Usage Examples

You can find usage examples at the end of the Jupyter Notebook (*main.ipynb*)

## Authors

- Szymon Szarek [szaross](https://github.com/szaross)
- Kacper Garus [gahson](https://github.com/gahson)

