error id: file:///mnt/a66ad743-1601-4348-99ee-1e8f5b440f29/UCSC/SCS%202204%20-%20Functional%20Programming/Practicals%20-%20Viva/22001239_Practical_10/negateFunction/NegateFunction.scala:[313..314) in Input.VirtualFile("file:///mnt/a66ad743-1601-4348-99ee-1e8f5b440f29/UCSC/SCS%202204%20-%20Functional%20Programming/Practicals%20-%20Viva/22001239_Practical_10/negateFunction/NegateFunction.scala", "class Rational(n:Int,d:Int){
    require(d != 0, "Denominator cannot be zero")

    private val gcd = greatestCommonDivisor(n.abs, d.abs);
    val numerator: Int = n/gcd;
    val denominator: Int = d/gcd;

    def this(n:Int)=this(n,1)

    def neg:Rational=new Rational(-numerator, denominator)

    private def
}
object NegateFunction{

    def main(args: Array[String]):Unit={
    
    }
}")
file:///mnt/a66ad743-1601-4348-99ee-1e8f5b440f29/UCSC/SCS%202204%20-%20Functional%20Programming/Practicals%20-%20Viva/22001239_Practical_10/negateFunction/NegateFunction.scala
file:///mnt/a66ad743-1601-4348-99ee-1e8f5b440f29/UCSC/SCS%202204%20-%20Functional%20Programming/Practicals%20-%20Viva/22001239_Practical_10/negateFunction/NegateFunction.scala:13: error: expected identifier; obtained rbrace
}
^
#### Short summary: 

expected identifier; obtained rbrace