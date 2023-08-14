# ***One-n-Only*** v-0.1

## **Modules**

1. ## ***Areas***
    ### basics areas of different shapes, functions:
    - ***`areas.square(side:int|float)`***
    - ***`areas.reactangle(length:int|float,breadth:int|breadth)`***
    - ***`areas.equiTriangle(length:int|float)`***
    - ***`areas.isoTriangle(a:int|float,b:int|float)`***
    - ***`areas.circle(radius:int|float)`***
    - ***`areas.semiCircle(radius:int|float)`***
    - ***`areas.quarterCircle(radius:int|float)`***
    - ***`areas.sector(radius:int|float,angle:int|float,unit:str = "str")`***

2. ## ***Const***
    ### constants variable
    - ***`const.PI`***
    - ***`const.E`***
    - ***`const.INFINITY`*** or ***`const.infinity`*** or ***`const.inf`***
    - ***`const.NAN`*** or ***`const.NaN`*** or ***`const.nan`***
    - ***`const.TRUE`*** or ***`const.true`*** or ***`const.YES`*** or ***`const.yes`***
    - ***`const.FALSE`*** or ***`const.false`*** or ***`const.NO`*** or ***`const.no`***
    - ***`const.me`***
    - ***`const.qe`***
    - ***`const.mp`***
    - ***`const.qp`***
    - ***`const.mn`***
    - ***`const.qn`***
    - ***`const.g`***  
    `and so on...`
    <!-- - ***`const.G`***
    - ***`const.h`***
    - ***`const.R`***
    - ***`const.c`***
    - ***`const.k`***
    - ***`const.ang`***
    - ***`const.tredecillion`***
    - ***`const.duodecillion`***
    - ***`const.undecillion`***
    - ***`const.decillion`***
    - ***`const.nonillion`***
    - ***`const.octillion`***
    - ***`const.septillion`***
    - ***`const.sextillion`***
    - ***`quintillion`*** or ***`exa`***
    - ***`quadrillion`*** or ***`peta`***
    - ***`trillion`*** or ***`tera`***
    - ***`billion`*** or ***`giga`***
    - ***`tenCrore`***
    - ***`crore`***
    - ***`tenLakh`*** or ***`million`*** or ***`mega`***
    - ***`lakh`*** or ***`hundredThousand`***
    - ***`tenThousand`***
    - ***`thousand`*** or ***`kilo`***
    - ***`hundred`*** or ***`hecto`***
    - ***`ten`*** or ***`deca`***
    - ***`one`***
    - ***`zero`***
    - ***`oneTenth`*** or ***`deci`***
    - ***`oneHundredth`*** or ***`centi`***
    - ***`oneThousandth`*** or ***`milli`***
    - ***`oneMillionth`*** or ***`micro`***
    - ***`oneBillionth`*** or ***`nano`***
    - ***`oneTrillionth`*** or ***`pico`***
    - ***`oneQuadrillionth`*** or ***`femto`***
    - ***`oneQuintillionth`*** or ***`atto`*** -->

3. ## ***Data***
    ### fetch data with `data` module
    - ***`data.fetch_data(file:str,ext:str = "csv",lim:str = ",")`***
    - ***`data.fetch_data_dir(directory:str = os.getcwd(),lim:str = ",")`***
    - ***`data.fetch_remote_dataset_lists()`***
    - ***`data.get_data_files_lists(directory:str = os.getcwd())`***

4. ## ***Linked-List***
    ### to store the data such as `int`,`float` and so on...
    1. ***`LinkedList.signlyLinkedList()`***
        - ***`.append(data)`***
        - ***`.display()`***
        - ***`.length()`***
        - ***`.isPresent(target)`***
        - ***`.indexOf(target)`***
        - ***`.valueAt(index:int)`***
        - ***`.remove(target)`***
    2. ***`LinkedList.doublyLinkedList()`***
        - ***`.append(data)`***
        - ***`.display()`***
        - ***`.length()`***
        - ***`.isPresent(target)`***
        - ***`.indexOf(target)`***
        - ***`.valueAt(index:int)`***
        - ***`.remove(target)`***

5. ## **List**
    ### perform the mathematical operation on lists using `List` module
    - ***`List.dotProduct(*lists:list)`***
    - ***`List.poduct(*lists)`***
    - ***`List.scalarProduct(lst:list,scalar:int|float=1)`***
    - ***`List.add(*lists:list)`***
    - ***`List.scalarAdd(lists:list,scalar:int|float=0)`***
    - ***`List.sub(*lists:list)`***
    - ***`List.scalarSub(lists:list,scalar:int|float=0)`***
    - ***`List.div(*lists:list)`***
    - ***`List.scalarDiv(lists:list,scalar:int|float=1)`***
    - ***`List.floorDiv(*lists:list)`***
    - ***`List.scalarFloorDiv(lists:list,scalar:int|float=1)`***
    - ***`List.modulo(*lists:list)`***
    - ***`List.scalarModulo(lists:list,scalar:int|float=1)`***
    - ***`List.pow(lists:list,scalar:int|float=1)`***
    - ***`List.flatten(lists:list)`***

6. ## **Maths**
    ### perform basics mathematics operations
    - ***`maths.sqrt(number:int|float,precision:float=1e-6)`***
    - ***`maths.cbrt(number:int|float,precision:float=1e-6)`***
    - ***`maths.factorial(number:int)`***
    - ***`maths.permuation(n:int,r:int)`***
    - ***`maths.combination(n:int,r:int)`***
    - ***`maths.power(base:int|float,exponent:int|float)`***
    - ***`maths.exp(x:int=1)`***
    - ***`maths.length(array:list)`***
    - ***`maths.summation(array:list)`***
    - ***`maths.product(array:list)`***
    - ***`maths.maxVal(array:list)`***
    - ***`maths.minVal(array:list)`***
    - ***`maths.ceil(number:int|float)`***
    - ***`maths.floor(number:int|float)`***
    - ***`maths.quadraticRoots(coefs:list)`***
    - ***`maths.isPrime(number:int)`***
    - ***`maths.primes(lowerBound:int,upperBound:int)`***
    - ***`maths.findPrimes(array:list)`***
    - ***`maths.isEven(number:int|float)`***
    - ***`maths.evens(lowerBound:int,upperBound:int)`***
    - ***`maths.findEvens(array:list)`***
    - ***`maths.isOdd(number:int|float)`***
    - ***`maths.odds(lowerBound:int,upperBound:int)`***
    - ***`maths.findOdds(array:list)`***
    - ***`maths.log(number:int|float)`***
    - ***`maths.ln(number:int|float)`***
    - ***`maths.logn(number:int|float)`***
    - ***`maths.deg2rad(angle:int|float)`***
    - ***`maths.rad2deg(angle:int|float)`***
    - ***`maths.sin(angle:int|float,unit:str="rad")`***
    - ***`maths.cos(angle:int|float,unit:str="rad")`***
    - ***`maths.tan(angle:int|float,unit:str="rad")`***
    - ***`maths.cot(angle:int|float,unit:str="rad")`***
    - ***`maths.sec(angle:int|float,unit:str="rad")`***
    - ***`maths.cosec(angle:int|float,unit:str="rad")`***

7. ## **Matrix**
    ### mathematics operations with matrices with `matrix` module
    - ***`matrix.isMatrix(matrix:list[list])`***
    - ***`matrix.toMatrix(matrix:list[list],dim:tuple)`***
    - ***`matrix.reshape(matrix:list[list],dim:tuple)`***
    - ***`matrix.isSquare(matrix:list[list])`***
    - ***`matrix.dim(matrix:list[list])`***
    - ***`matrix.shape(matrix:list[list])`***
    - ***`matrix.size(matrix:list[list])`***
    - ***`matrix.info(matrix:list[list])`***
    - ***`matrix.zeros(shape:tuple)`***
    - ***`matrix.ones(shape:tuple)`***
    - ***`matrix.dummy(shape:tuple,value:int|float)`***
    - ***`matrix.add(*matrices:list[list])`***
    - ***`matrix.scalarAdd(matrix:list[list],scalar:int|float=0)`***
    - ***`matrix.sub(*matrices:list[list])`***
    - ***`matrix.scalarSub(matrix:list[list],scalar:int|float=0)`***
    - ***`matrix.product(*matrices:list[list])`***
    - ***`matrix.scalarProduct(matrix:list[list],scalar:int|float=1)`***
    - ***`matrix.T(matrix:list[list])`***
    - ***`matrix.subMatrix(matrix:list[list],shape:tuple)`***
    - ***`matrix.det(matrix:list[list])`***
    - ***`matrix.cofactor(matrix:list[list])`***
    - ***`matrix.adjoint(matrix:list[list])`***
    - ***`matrix.inv(matrix:list[list])`***
    - ***`matrix.traces(matrix:list[list])`***
    - ***`matrix.diagonalSum(matrix:list[list])`***
    - ***`matrix.removeCol(matrix:list[list],column:int)`***
    - ***`matrix.removeRow(matrix:list[list],row:int)`***
    - ***`matrix.reciprocal(matrix:list[list])`***

## and so on...


