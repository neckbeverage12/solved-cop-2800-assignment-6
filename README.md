Download Link: https://assignmentchef.com/product/solved-cop-2800-assignment-6
<br>
Go Dolphins!!!This assignment is a simulation of beer drinking football fans and the security guards that love them.

Design Requirements:Class Beer – Tracks whether it is full or empty and has a getter.  Also, has a drink method.Class SixPack – Starts with an array of 6 beers, dispenses beers up to 6, and has a toString.Class Person – Has a first and last name, getters, and a toStringClass NFLFan – Extends Person, drinks beers and keeps count, getter and toStringClass StadiumSecurity – Extends Person, chews out fans who’ve had more than 2 beers, getter and toString

<sup> </sup>

Please title your java file Assignment6.java.  Submitted files that do not compile will receive a grade of 0.




Next page – sample output and the driver used to generate it




No output from the class definitions.  All the output was done from this driver:




public class Assignment6 {

public static void main (String [] arg) {

SixPack sixPack = new SixPack();

NFLFan steve = new NFLFan(“steve”, “harris”);

NFLFan rick = new NFLFan(“rick”, “newhouse”);

StadiumSecurity bobTheSecurityGuard =

new StadiumSecurity(“bob”, “modino”);




steve.drinkBeer (sixPack.getABeer());

System.out.println(steve);

System.out.println(sixPack);




rick.drinkBeer (sixPack.getABeer());

rick.drinkBeer (sixPack.getABeer());

rick.drinkBeer (sixPack.getABeer());

System.out.println(rick);

System.out.println(sixPack);




bobTheSecurityGuard.challengeBeerDrinker (steve);

bobTheSecurityGuard.challengeBeerDrinker (rick);

System.out.println(bobTheSecurityGuard);

}

}Note:  This is <strong>not</strong> the driver I will use to test your program.   I will check for these implementation errors:

<ul>

 <li>A fan upping his beer count by drinking an empty beer</li>

 <li>A six pack that dispenses more than six beers</li>

 <li>A security guard yelling at a fan who is under the beer limit</li>

 <li>etc</li>

</ul>


