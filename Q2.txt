Class Square
{
Public void Area(double side)
{
Double calArea = side * side;
System.out.println(“Area of Square is:\t”+calArea);
}
Public void Perimeter(double side)
 {
 Double calPerimeter = 4 * side;
 System.out.println(“Perimeter of Square is:\t”+calPerimeter);
}
}
Class Rectangle 
{
Public void Area(double length, double breadth)
{
Double calArea = length * breadth;
System.out.println(“Area of Rectangle is:\t”+calArea);
}
Public void Perimeter(double length, double breadth)
{
 Double calPerimeter = 2 * (length + breadth);
 System.out.println(“Area of Rectangle is:\t”+calPerimeter);
}
}
Class MainClass
{
Public static void main(String[] args) 
{
Square obj1 = new Square();
Rectangle obj2 = new Rectangle();
Obj1.Area(4.0);
Obj1.Perimeter(3.0);
Obj2.Area(7.0,2.0);
Obj2.Perimeter(4.0,1.0);
}
}