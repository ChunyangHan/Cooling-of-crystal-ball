# Cooling-of-crystal-ball
The cooling of crystal glass needs attention in the production process. Quick cooling is wanted to keep the cost lower but may cause the glass to break. A crystal ball with radius R shall be cooled down from 980∘C to room temperature. The temperature lowering in the oven takes place in a controlled way and depends on the adjusted temperature parameter T that starts at t = 0 until t = T according to
f (t) = 980e−3.9t∕T\\
For t > T, we have f (t) = 980e−3.9 = 19.8, hence normal room temperature.
The heat equation for a homogeneous sphere follows the PDE
𝜕u/𝜕t= D/r*𝜕2(ru)/𝜕r2 , 0 < r < R, t > 0
The thermal diffusivity for crystal glass is D = 4.0 ⋅ 10−7 m2∕s. At r = 0, we have the BC 𝜕u/𝜕r= 0. Hence, at this Boundary, the heat equation takes the form 𝜕u/𝜕t= 3D𝜕2u/𝜕r2
Prove this with the help of l’Hopital’s rule. The BC at r = R is u(R, t) = f (t). When the cooling starts, the temperature of the ball is 980∘C.
Of special interest is the temperature gradient in the r direction—the glass may break if||𝜕u/𝜕r|| is too large. In our case, we assume that the glass will break if the gradient on any occasion exceeds 6000∘C, which will happen if the cooling is too quick.Make numerical experiments with the parameter T and find the smallest value of T in the cases R = 6, 12, and 18 cm.
Compute the temperature u(r, t) in the glass ball from t = 0 until its surface has cooled down to room temperature.
Try discretization with 60 intervals in the r direction. Use the MoL and an appropriate ODE solver or use the implicit Euler method with small time steps in the beginning and then increase the time step.
Visualize the result graphically.
