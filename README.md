Ok, so I'll document this one a bit before.


So we can observe that each box segment of the spiral contains an odd square number at the corner. We first want to find which spiral (iow which square number's box) our integer is located in. (sqrt, rounddown,  power of 2, then we  check if even or odd and sqrt, add 1, power 2 if needed). Then we check the distance (diagonaly) our square number is to the center 1 (sqrt -1 /2). We then check which side our integer is located (up down left right). After having located it's region, we see how far it is to the center of the side and take it's absolute value. We then add up that with "the distance our square number is to the center" and tada!
