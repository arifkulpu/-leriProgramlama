# -leriProgramlama
İleri programlama Final
Project Euler Soruları :

Soru 3 :
Largest prime factor
    
Problem 3
The prime factors of 13195 are 5, 7, 13 and 29.
What is the largest prime factor of the number 600851475143 ?
Cevap : (6857)
Soru 3 : 

const isPrime = (değer) => {
  for (let i = 2; i <değer; i ++)
    eğer (% i === 0 değeri)
      yanlış döndür;
  geri dönüş;
};

const LargestPrimeFactor = (değer) => {
  sonuç = [];  
  for (let i = 2; i <değer; i ++)
    if (isPrime (i))
      eğer (% i === 0 değeri)
        sonuç. it (i);
  sonuç;
};
console.log (LargestPrimeFactor (600851475143));
Cevap : 6857

Soru 13 :
Large sum
    
Problem 13
Work out the first ten digits of the sum of the following one-hundred 50-digit numbers.
37107287533902102798797998220837590246510135740250
46376937677490009712648124896970078050417018260538
74324986199524741059474233309513058123726617309629
91942213363574161572522430563301811072406154908250
23067588207539346171171980310421047513778063246676
89261670696623633820136378418383684178734361726757
28112879812849979408065481931592621691275889832738
44274228917432520321923589422876796487670272189318
47451445736001306439091167216856844588711603153276
70386486105843025439939619828917593665686757934951
62176457141856560629502157223196586755079324193331
64906352462741904929101432445813822663347944758178
92575867718337217661963751590579239728245598838407
58203565325359399008402633568948830189458628227828
80181199384826282014278194139940567587151170094390
35398664372827112653829987240784473053190104293586
86515506006295864861532075273371959191420517255829
71693888707715466499115593487603532921714970056938
54370070576826684624621495650076471787294438377604
53282654108756828443191190634694037855217779295145
36123272525000296071075082563815656710885258350721
45876576172410976447339110607218265236877223636045
17423706905851860660448207621209813287860733969412
81142660418086830619328460811191061556940512689692
51934325451728388641918047049293215058642563049483
62467221648435076201727918039944693004732956340691
15732444386908125794514089057706229429197107928209
55037687525678773091862540744969844508330393682126
18336384825330154686196124348767681297534375946515
80386287592878490201521685554828717201219257766954
78182833757993103614740356856449095527097864797581
16726320100436897842553539920931837441497806860984
48403098129077791799088218795327364475675590848030
87086987551392711854517078544161852424320693150332
59959406895756536782107074926966537676326235447210
69793950679652694742597709739166693763042633987085
41052684708299085211399427365734116182760315001271
65378607361501080857009149939512557028198746004375
35829035317434717326932123578154982629742552737307
94953759765105305946966067683156574377167401875275
88902802571733229619176668713819931811048770190271
25267680276078003013678680992525463401061632866526
36270218540497705585629946580636237993140746255962
24074486908231174977792365466257246923322810917141
91430288197103288597806669760892938638285025333403
34413065578016127815921815005561868836468420090470
23053081172816430487623791969842487255036638784583
11487696932154902810424020138335124462181441773470
63783299490636259666498587618221225225512486764533
67720186971698544312419572409913959008952310058822
95548255300263520781532296796249481641953868218774
76085327132285723110424803456124867697064507995236
37774242535411291684276865538926205024910326572967
23701913275725675285653248258265463092207058596522
29798860272258331913126375147341994889534765745501
18495701454879288984856827726077713721403798879715
38298203783031473527721580348144513491373226651381
34829543829199918180278916522431027392251122869539
40957953066405232632538044100059654939159879593635
29746152185502371307642255121183693803580388584903
41698116222072977186158236678424689157993532961922
62467957194401269043877107275048102390895523597457
23189706772547915061505504953922979530901129967519
86188088225875314529584099251203829009407770775672
11306739708304724483816533873502340845647058077308
82959174767140363198008187129011875491310547126581
97623331044818386269515456334926366572897563400500
42846280183517070527831839425882145521227251250327
55121603546981200581762165212827652751691296897789
32238195734329339946437501907836945765883352399886
75506164965184775180738168837861091527357929701337
62177842752192623401942399639168044983993173312731
32924185707147349566916674687634660915035914677504
99518671430235219628894890102423325116913619626622
73267460800591547471830798392868535206946944540724
76841822524674417161514036427982273348055556214818
97142617910342598647204516893989422179826088076852
87783646182799346313767754307809363333018982642090
10848802521674670883215120185883543223812876952786
71329612474782464538636993009049310363619763878039
62184073572399794223406235393808339651327408011116
66627891981488087797941876876144230030984490851411
60661826293682836764744779239180335110989069790714
85786944089552990653640447425576083659976645795096
66024396409905389607120198219976047599490197230297
64913982680032973156037120041377903785566085089252
16730939319872750275468906903707539413042652315011
94809377245048795150954100921645863754710598436791
78639167021187492431995700641917969777599028300699
15368713711936614952811305876380278410754449733078
40789923115535562561142322423255033685442488917353
44889911501440648020369068063960672322193204149535
41503128880339536053299340368006977710650566631954
81234880673210146739058568557934581403627822703280
82616570773948327592232845941706525094512325230608
22918802058777319719839450180888072429661980811197
77158542502016545090413245809786882778948721859617
72107838435069186155435662884062257473692284509516
20849603980134001723930671666823555245252804609722
53503534226472524250874054075591789781264330331690
Cevap:

Const  num =  
	
	“37107287533902102798797998220837590246510135740250\n” +
	“46376937677490009712648124896970078050417018260538\n” +
	“74324986199524741059474233309513058123726617309629\n” +
	“91942213363574161572522430563301811072406154908250\n” +
	“23067588207539346171171980310421047513778063246676\n” +
	“89261670696623633820136378418383684178734361726757\n” +
	“28112879812849979408065481931592621691275889832738\n” +
	“44274228917432520321923589422876796487670272189318\n” +
	“47451445736001306439091167216856844588711603153276\n” +
	“70386486105843025439939619828917593665686757934951\n” +
	“62176457141856560629502157223196586755079324193331\n” +
	“64906352462741904929101432445813822663347944758178\n” +
	“92575867718337217661963751590579239728245598838407\n” +
	“58203565325359399008402633568948830189458628227828\n” +
	“80181199384826282014278194139940567587151170094390\n” +
	“35398664372827112653829987240784473053190104293586\n” +
	“86515506006295864861532075273371959191420517255829\n” +
	“71693888707715466499115593487603532921714970056938\n” +
	“54370070576826684624621495650076471787294438377604\n” +
	“53282654108756828443191190634694037855217779295145\n” +
	“36123272525000296071075082563815656710885258350721\n” +
	“45876576172410976447339110607218265236877223636045\n” +
	“17423706905851860660448207621209813287860733969412\n” +
	“81142660418086830619328460811191061556940512689692\n” +
	“51934325451728388641918047049293215058642563049483\n” +
	“62467221648435076201727918039944693004732956340691\n” +
	“15732444386908125794514089057706229429197107928209\n” +
	“55037687525678773091862540744969844508330393682126\n” +
	“18336384825330154686196124348767681297534375946515\n” +
	“80386287592878490201521685554828717201219257766954\n” +
	“78182833757993103614740356856449095527097864797581\n” +
	“16726320100436897842553539920931837441497806860984\n” +
	“48403098129077791799088218795327364475675590848030\n” +
	“87086987551392711854517078544161852424320693150332\n” +
	“59959406895756536782107074926966537676326235447210\n” +
	“69793950679652694742597709739166693763042633987085\n” +
	“41052684708299085211399427365734116182760315001271\n” +
	“65378607361501080857009149939512557028198746004375\n” +
	“35829035317434717326932123578154982629742552737307\n” +
	“94953759765105305946966067683156574377167401875275\n” +
	“88902802571733229619176668713819931811048770190271\n” +
	“25267680276078003013678680992525463401061632866526\n” +
	“36270218540497705585629946580636237993140746255962\n” +
	“24074486908231174977792365466257246923322810917141\n” +
	“91430288197103288597806669760892938638285025333403\n” +
	“34413065578016127815921815005561868836468420090470\n” +
	“23053081172816430487623791969842487255036638784583\n” +
	“11487696932154902810424020138335124462181441773470\n” +
	“63783299490636259666498587618221225225512486764533\n” +
	“67720186971698544312419572409913959008952310058822\n” +
	“95548255300263520781532296796249481641953868218774\n” +
	“76085327132285723110424803456124867697064507995236\n” +
	“37774242535411291684276865538926205024910326572967\n” +
	“23701913275725675285653248258265463092207058596522\n” +
	“29798860272258331913126375147341994889534765745501\n” +
	“18495701454879288984856827726077713721403798879715\n” +
	“38298203783031473527721580348144513491373226651381\n” +
	“34829543829199918180278916522431027392251122869539\n” +
	“40957953066405232632538044100059654939159879593635\n” +
	“29746152185502371307642255121183693803580388584903\n” +
	“41698116222072977186158236678424689157993532961922\n” +
	“62467957194401269043877107275048102390895523597457\n” +
	“23189706772547915061505504953922979530901129967519\n” +
	“86188088225875314529584099251203829009407770775672\n” +
	“11306739708304724483816533873502340845647058077308\n” +
	“82959174767140363198008187129011875491310547126581\n” +
	“97623331044818386269515456334926366572897563400500\n” +
	“42846280183517070527831839425882145521227251250327\n” +
	“55121603546981200581762165212827652751691296897789\n” +
	“32238195734329339946437501907836945765883352399886\n” +
	“75506164965184775180738168837861091527357929701337\n” +
	“62177842752192623401942399639168044983993173312731\n” +
	“32924185707147349566916674687634660915035914677504\n” +
	“99518671430235219628894890102423325116913619626622\n” +
	“73267460800591547471830798392868535206946944540724\n” +
	“76841822524674417161514036427982273348055556214818\n” +
	“97142617910342598647204516893989422179826088076852\n” +
	“87783646182799346313767754307809363333018982642090\n” +
	“10848802521674670883215120185883543223812876952786\n” +
	“71329612474782464538636993009049310363619763878039\n” +
	“62184073572399794223406235393808339651327408011116\n” +
	“66627891981488087797941876876144230030984490851411\n” +
	“60661826293682836764744779239180335110989069790714\n” +
	“85786944089552990653640447425576083659976645795096\n” +
	“66024396409905389607120198219976047599490197230297\n” +
	“64913982680032973156037120041377903785566085089252\n” +
	“16730939319872750275468906903707539413042652315011\n” +
	“94809377245048795150954100921645863754710598436791\n” +
	“78639167021187492431995700641917969777599028300699\n” +
	“15368713711936614952811305876380278410754449733078\n” +
	“40789923115535562561142322423255033685442488917353\n” +
	“44889911501440648020369068063960672322193204149535\n” +
	“41503128880339536053299340368006977710650566631954\n” +
	“81234880673210146739058568557934581403627822703280\n” +
	“82616570773948327592232845941706525094512325230608\n” +
	“22918802058777319719839450180888072429661980811197\n” +
	“77158542502016545090413245809786882778948721859617\n” +
	“72107838435069186155435662884062257473692284509516\n” +
	“20849603980134001723930671666823555245252804609722\n” +
	“53503534226472524250874054075591789781264330331690”;
	
	let steps = num.split(“\n”);
	
	let sum = 0;
	
	for (let i in steps) {
	// Add each 50 Digits number to the sum;
	sum += Number(steps[i]);
	}
	
	// Let’s remove the dot since it’s exponential
	let result = Number(String(sum).replace(/\./g, “”).slice(0, 10));
	
	console.log(result);

Cevap = 5537376230















Soru 23 :
Non-abundant sums
    
Problem 23
A perfect number is a number for which the sum of its proper divisors is exactly equal to the number. For example, the sum of the proper divisors of 28 would be 1 + 2 + 4 + 7 + 14 = 28, which means that 28 is a perfect number.
A number n is called deficient if the sum of its proper divisors is less than n and it is called abundant if this sum exceeds n.
As 12 is the smallest abundant number, 1 + 2 + 3 + 4 + 6 = 16, the smallest number that can be written as the sum of two abundant numbers is 24. By mathematical analysis, it can be shown that all integers greater than 28123 can be written as the sum of two abundant numbers. However, this upper limit cannot be reduced any further by analysis even though it is known that the greatest number that cannot be expressed as the sum of two abundant numbers is less than this limit.
Find the sum of all the positive integers which cannot be written as the sum of two abundant numbers.
Cevap : (4179871)
function getSumOfDivisors(num) {
 let sumOfDivisors = 1;
 let i;
 for (i = 2; i <= Math.sqrt(num); i++)
 if (num % i === 0) sumOfDivisors += i + num / i;
 if ((i - 1 === Math.sqrt(num)) & (num !== 1)) sumOfDivisors -= i - 1; return sumOfDivisors; 
}
 function canBeSummed(num, abundantNumbers) {
 let l = 0; 
let r = abundantNumbers.length - 1;
 while (l < r) {
 if (abundantNumbers[l] * 2 == num) return true; 
if (abundantNumbers[r] * 2 == num) return true;
 if (abundantNumbers[l] + abundantNumbers[r] == num) return true;
 if (abundantNumbers[l] + abundantNumbers[r] < num) l++;
 else r--;
 } 
return false; 
}
 let abundantNumbers = [];
 for (let i = 1; i <= 28123; i++) {
 if (i < getSumOfDivisors(i)) abundantNumbers.push(i);
 } 
abundantNumbers.sort((a, b) => a - b);
 let result = [];
 for (let num = 1; num <= 20161; num++) {
 if (!canBeSummed(num, abundantNumbers)) {
 result.push(num);
 } 
}
 console.log('total', result.reduce((a, b) => a + b));






Soru 33 :
Digit cancelling fractions
    
Problem 33
The fraction 49/98 is a curious fraction, as an inexperienced mathematician in attempting to simplify it may incorrectly believe that 49/98 = 4/8, which is correct, is obtained by cancelling the 9s.
We shall consider fractions like, 30/50 = 3/5, to be trivial examples.
There are exactly four non-trivial examples of this type of fraction, less than one in value, and containing two digits in the numerator and denominator.
If the product of these four fractions is given in its lowest common terms, find the value of the denominator.

Cevap : (100)
public static void main(String[] args) {
 int numProduct = 1, denomProduct = 1;
 for (int denom1 = 1; denom1 < 10; denom1++) {
 		int num2 = denom1;
 		for (int denom2 = 1; denom2 < 10; denom2++) {
 			for (int num1 = 1; num1 < num2; num1++) {
 if ((num1 * 10.0 + num2) / (denom1 * 10.0 + denom2) == (double) num1 / denom2) {
 System.out.println(num1 + "" + num2 + "/" + denom1 + "" + denom2); numProduct *= (num1 * 10 + num2);
 denomProduct *= (denom1 * 10 + denom2); } } } System.out.println(numProduct + "/" + denomProduct); 
} 
} 
Soru 43 :
Sub-string divisibility
    
Problem 43
The number, 1406357289, is a 0 to 9 pandigital number because it is made up of each of the digits 0 to 9 in some order, but it also has a rather interesting sub-string divisibility property.
Let d1 be the 1st digit, d2 be the 2nd digit, and so on. In this way, we note the following:
•	d2d3d4=406 is divisible by 2
•	d3d4d5=063 is divisible by 3
•	d4d5d6=635 is divisible by 5
•	d5d6d7=357 is divisible by 7
•	d6d7d8=572 is divisible by 11
•	d7d8d9=728 is divisible by 13
•	d8d9d10=289 is divisible by 17
Find the sum of all 0 to 9 pandigital numbers with this property.
Cevap : 16695334890
import java.util.TreeSet;
import java.math.BigInteger;
 public class Main {
 public static void savePermutations(TreeSet<BigInteger> permutations, int length, char[] elements) {
 if (length == 1) { 
if (elements[0] != '0'){ permutations.add(new BigInteger(new String(elements))); 
} 
} else {
 for (int i = 0; i < length - 1; i++) { savePermutations(permutations, length - 1, elements);
 if (length % 2 == 0) { 
swap(elements, i, length - 1);
 } else { 
swap(elements, 0, length - 1);
 } 
}
 savePermutations(permutations, length - 1, elements);
 } 
}
 public static void swap(char[] input, int a, int b) { 
char tmp = input[a];
 input[a] = input[b];
 input[b] = tmp;
 } 
public static boolean hasProperty(BigInteger number){
 int[] primes = new int[]{2,3,5,7,11,13,17};
 String numString = String.valueOf(number);
 for (int i = 1; i <= 7; i++){
 if (Integer.parseInt("" + numString.charAt(i) + numString.charAt(i+1) + numString.charAt(i+2)) % primes[i-1] != 0){
 return false; 
} 
} 
return true; 
} 
public static void main(String[] args) {
 TreeSet<BigInteger> perms = new TreeSet();
 char[] numCharArray = new char[]
{'1','2','3','4','5','6','7','8','9','0'}; 
savePermutations(perms, numCharArray.length, numCharArray);
 BigInteger sum = BigInteger.ZERO;
 for (BigInteger panDig : perms) { 
if (hasProperty(panDig)){
 sum = sum.add(panDig);
 } 
}
 System.out.println(sum); 
} 
}
LEETCODE Soruları :
Soru 3 :
 Longest Substring Without Repeating Characters
Given a string, find the length of the longest substring without repeating characters.
Cevap : "abcabcbb"
/**
 * @param {string} s
 * @return {number}
 */
var lengthOfLongestSubstring = function(s) {
    let max_len = 0;
    let curr = 0;
    let hash = {}; 
    if(s.length < 2) {
        return s.length;
    }
    for(let i = 0; i < s.length;  i++) {
        if(hash[s[i]] == null) {
            curr += 1;
        } else {
            curr = Math.min(i - hash[s[i]], curr + 1);
        }
        max_len = Math.max(max_len, curr);
        hash[s[i]] = i; //save the index
    }
    return max_len;
};























Soru 13 :
Roman to Integer Roman numerals are represented by seven different symbols: I, V, X, L, C, D and M.
Symbol       Value
I             1
V             5
X             10
L             50
C             100
D             500
M             1000
For example, two is written as II in Roman numeral, just two one's added together. Twelve is written as, XII, which is simply X + II. The number twenty seven is written as XXVII, which is XX + V + II.
Roman numerals are usually written largest to smallest from left to right. However, the numeral for four is not IIII. Instead, the number four is written as IV. Because the one is before the five we subtract it making four. The same principle applies to the number nine, which is written as IX. There are six instances where subtraction is used:
•	I can be placed before V (5) and X (10) to make 4 and 9. 
•	X can be placed before L (50) and C (100) to make 40 and 90. 
•	C can be placed before D (500) and M (1000) to make 400 and 900.
Given a roman numeral, convert it to an integer. Input is guaranteed to be within the range from 1 to 3999.
Cevap : "III", “3”
/**
 * @param {string} s
 * @return {number}
 */
var romanToInt = function(s) {
    s = s.split('');
    let total = 0;
    rVals = {
        I:1,
        V:5,
        X:10,
        L:50,
        C:100,
        D:500,
        M:1000
    }
    for (let i=s.length-1;i>=0;i--) {
        total += (rVals[s[i]] < (rVals[s[i+1]||0])? -rVals[s[i]] : rVals[s[i]]);
    }
    return total;
};
















Soru 23 :
 Merge k Sorted Lists Merge k sorted linked lists and return it as one sorted list. Analyze and describe its complexity.
Cevap : [1,1,2,3,4,4,5,6]
class MinHeap{
    constructor(){
        this.heap = [];
    }
    
  // O(log(n)) time | O(1) space 
  siftUp(currentIdx, heap){
    let parentIdx = Math.floor((currentIdx - 1) / 2);
       while(parentIdx >= 0 && heap[parentIdx] > heap[currentIdx]){
            this.swap(parentIdx, currentIdx, heap);
           currentIdx = parentIdx;
           parentIdx = Math.floor((currentIdx - 1) / 2);
        }
    }
    
  // O(log(n)) time | O(1) space 
  siftDown(parentIdx, endIdx, heap){
      let childOneIdx = (parentIdx * 2) +1;
      while(childOneIdx <= endIdx){
          let childTwoIdx = (parentIdx * 2) +2 <= endIdx ?(parentIdx * 2) +2 : -1;
          let idxToSwap;
          if(childTwoIdx != -1 && heap[childTwoIdx] < heap[childOneIdx]){
              idxToSwap = childTwoIdx; 
          }else{
              idxToSwap = childOneIdx
          }
          if(heap[parentIdx] > heap[idxToSwap]){
              this.swap(parentIdx, idxToSwap, heap);
              parentIdx = idxToSwap;
              childOneIdx = (parentIdx * 2) +1;
          }else{
              return;
          }
      }
  }
    
    // O(log(n)) time | O(1) space 
    insert(value){
        this.heap.push(value);
        this.siftUp(this.heap.length-1, this.heap);
    }
    
    // O(log(n)) time | O(1) space 
    remove(){
        this.swap(0, this.heap.length-1, this.heap);
        let removedVal = this.heap.pop();
        this.siftDown(0, this.heap.length-1, this.heap);
        return removedVal;
    }
    
    // O(1) time | O(1) space 
    size(){
        return this.heap.length;
    }
    
    // O(1) time | O(1) space 
    swap(i, j, arr){
        let temp = arr[i];
        arr[i] = arr[j];
        arr[j] = temp
    }
}
     
     
class LinkedList{
    constructor(val, next){
        this.val = val;
        this.next = next
    }
}

// O(NlogN) time | O(N) space in which N is the length of all values in all lists
var mergeKLists = function(lists) {
    let pq = new MinHeap();


    for(let list of lists){
      while(list != null){
          pq.insert(list.val);
          list = list.next;
      }
    }
    
    let mergedList = new LinkedList(0, null);
    let head = mergedList;
    while(pq.size() > 0){
        let val = pq.remove();
        head.next = new LinkedList(val, null);
        head = head.next;
    }
    
    return mergedList.next;
};




Soru 33 :
Search in Rotated Sorted Array uppose an array sorted in ascending order is rotated at some pivot unknown to you beforehand.
(i.e., [0,1,2,4,5,6,7] might become [4,5,6,7,0,1,2]).
You are given a target value to search. If found in the array return its index, otherwise return -1.
You may assume no duplicate exists in the array.
Your algorithm's runtime complexity must be in the order of O(log n).
Cevap : 4
/**
 * @param {number[]} nums
 * @param {number} target
 * @return {number}
 */
var search = function (nums, target) {
  const minIndex = findMinimum(nums)
  if (nums[minIndex] === target) return minIndex;
  if (target > nums[minIndex] && target > nums[nums.length - 1]) { //if greater than than the mid and last
    let index = binarySearch(0, minIndex, nums, target) //search the first half of the array
    if (index !== -1) return index
  } else {
    let index = binarySearch(minIndex, nums.length, nums, target) //search the remainder of the array
    return index;
  }
  return -1
};

function findMinimum(arr) {
  let l = 0;
  let r = arr.length - 1;
  while (l < r) {
    const mid = Math.floor((r + l) / 2)
    if (arr[mid] > arr[r]) {
      l = mid + 1
    } else {
      r = mid
    }
  }
  return l
}

function binarySearch(l, r, arr, target) {
  while (l <= r) {
    const mid = Math.floor((r + l) / 2)
    if (arr[mid] === target) {
      return mid
    } else if (arr[mid] > target) {
      r = mid - 1
    } else {
      l = mid + 1
    }
  }
  return -1}
Soru 53 :
Maximum Subarray Given an integer array nums, find the contiguous subarray (containing at least one number) which has the largest sum and return its sum.
Cevap : 6
/**
 * @param {number[]} nums
 * @return {number}
 */
 var maxSubArray = function(nums) {
    if (nums.length ==1) return nums[0];
    let currMax = nums[0];
    let history = nums[0];
    for (i=1, z=nums.length; i<z; i++){
        history = Math.max(history+nums[i], nums[i]);
        currMax = Math.max(history, currMax)
    }
    return currMax;
};
