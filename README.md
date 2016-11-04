# fiche3
public  class Segment {
    public Point A = new.Point();
    public Point B = new.Point();
}
public Segment (Point A,Point B) {
    this.A = A;
    this.B = B;
}
public double distance (Point A,Point B ){
    return math.sqrt(
            (math.pow((B.getabs()- A.getabs ()),2)+(math.pow((B.geto()-A.getord()),2)));
}
     public Segment symetrie(Point A, Point B) {

         return new Segment((A.symertie()), (B.symertie()));
     }
