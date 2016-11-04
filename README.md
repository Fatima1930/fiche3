package ficheTd3;

public class Point{
    private float abs ;
    private float ord ;
    public Point () {
        this.abs = 0;
        this.ord= 0;
    }
    public  Point (float abs ) {
        this.abs = abs;
        this.ord = abs;

    }
    public Point(float abs ,float ord) {
        this.abs = abs;
        this.ord = ord;
    }
    public Point symetrie() {
        return new Point(-abs, ord);
    }
   public  String toString (){
       return "("+ abs +","+ ord +")";
       public float  getabs() {
        return abs ;
    }
    public float getord() {
        return ord ;
    }

}
 public  class Segment {
    public Point A = new.Point();
    public Point B = new.Point();
}
public Segment (Point A,Point B) {
    this.A = A;
    this.B = B;//
}
public double distance (Point A,Point B ){
    return math.sqrt(
            (math.pow((B.getabs()- A.getabs ()),2)+(math.pow((B.geto()-A.getord()),2)));
}
     public Segment symetrie(Point A, Point B) {

         return new Segment((A.symertie()), (B.symertie()));
     }
