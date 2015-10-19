# Punto-Q.5.67
Further Analysis
Q.5.67 Load and run the program of Example 5.11.
T = linspace(0,12*pi,400);

>> Z =T;

>> R = exp(-T/7);

>> X = R.*cos(2*T);

>> Y= R.*sin(2*T);

>> subplot (2,2,1); plot3(X,Y,Z)

>> grid on

>> xlabel (‘X’), ylabel(‘Y’), zlabel(‘Z’)

>> title (‘3D view for Example 5.11’)

>> subplot(2,2,2); plot3(X,Y,Z); view(0,90)

>> grid on

>> xlabel (‘X’),ylabel(‘Y’)

>> title (‘XY Plane Projection’)

>> subplot

(2,2,3); plot3(X,Y,Z); view(0,0)

>> grid on

>> xlabel(‘X’),zlabel(‘Z’)

>> title(‘XZ Plane Projection’)

>> subplot(2,2,4); plot3(X,Y,Z); view(30,120)

>> grid on

>> xlabel(‘X’),ylabel(‘Y’),zlabel(‘Z’)

>> title(‘3D Plot Using View (30,120)’)
