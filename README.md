# Inheritance-geometric-shapes-problem-class Circle{

    int r;

    int h;

    public void area(int r){

        int area=(int )(3.14*r*r);

        System.out.println("Area of the circle is: "+area);

    }

    public void pmeter(int r){

        int pmeter=(int)(2*3.14*r);

        System.out.println("Perimeter of the cicle is : "+ pmeter);

    }

}

class Cylinder extends Circle {

    public void areaca(int r, int h) {

        int ca = (int) (2 * 3.14 * r * h);

        System.out.println("Curved surface area of the cylinder is : "+ ca);

    }

    public void areata(int r, int h) {

        int ta = (int) (2 * 3.14 * r * r + h);

        System.out.println("Total surface area of the cylinder is : "+ ta);

    }

    public void volume(int r, int h) {

        int vol = (int) (3.14 * r * r * h);

        System.out.println("Volume of the cylinder is :" + vol);

    }

}

class Code{

    public static void main(String... args){

        Circle c=new Circle();

        Cylinder l=new Cylinder();

        c.area(4);

        c.pmeter(4);

        l.areaca(2,3);

        l.areata(2,3);

        l.volume(2,3);

    }

}
