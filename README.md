# ArrayList-in-Java
import java.util.ArrayList;
import java.util.Collections;

public class ReverseAnArrayList{
public static void main(String[]args){

//create an ArrayList object
ArrayList arrayList = new ArrayList();

//Add elements to Arraylist
arrayList.add("A");
arrayList.add("B");
arrayList.add("C");
arrayList.add("D");
arrayList.add("E");

System.out.printIn("Before Reverse Order, ArrayList Contains :" +arrayList);

//Reverse the order of all elements of ava ArrayList

Collections.reverse(arrayList);

System.out.printIn("After Reverse Order,ArrayList Contains:"+arrayList);
}
}

