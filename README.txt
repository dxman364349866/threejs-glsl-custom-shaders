University of British Columbia, Vancouver
Winter 2017 Term 2
CPSC 314 Computer Graphics
Assignment #5
Student Name: Zafer Cavdar
Student ID: 51503035
CS Username: g0o1b

For part g:
  I created a new torus whose texture is calculated based on 3D custom perlin noise function.
  Perlin Noise function takes position and time as an input and returns noise value. Color is
  calculated based on light intensity and noise. Thus, my torus surface has animated and procedural
  texture.
  I also changed my custom shader so that it defines 3 circular surface with on top of the torus and
  these circular regions' positions depend on time variable that passed as uniform variable.
  Orange circle represents hour hand.
  Pink circle represents minute hand.
  Green circle represents second hand.

Acknowledgements:
Source of Perlin Noise function code:
    https://gist.github.com/patriciogonzalezvivo/670c22f3966e662d2f83
