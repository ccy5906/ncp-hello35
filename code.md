  ### App2
  ```C#
  
  /*
           var number = 100;
          // number = "100";   //이미 int형이 되어버렸기 때문에 문자열을 넣을 수 없음

           var lotto = 10000000000L;
           var str = "안녕하세요";
           var this_double = 3.141592;
           var this_float = 3.14F;
           var this_bool = true;
           var this_char = 'H';


           Console.WriteLine("number: " + number.GetType());
           Console.WriteLine("lotto: " + lotto.GetType());
           Console.WriteLine("str: " + str.GetType());
           Console.WriteLine("this_double: " + this_double.GetType());
           Console.WriteLine("this_float: " + this_float.GetType());
           Console.WriteLine("this_bool: " + this_bool.GetType());
           Console.WriteLine("this_char: " + this_char.GetType());
           */

            /*
            Console.WriteLine("int형 최대" + int.MaxValue);
            Console.WriteLine("int형 최소" + int.MinValue);
            Console.WriteLine("long형 최대" + long.MaxValue);  //7로 끝나는데
            Console.WriteLine("long형 최소" + long.MinValue);   //8로 끝남
            Console.WriteLine("float형 최대" + float.MaxValue);  //E+38 (=10의 38승) float이 long보다 압도적으로 큼
            Console.WriteLine("float형 최소" + float.MinValue);  //최대 최소가 같음
            Console.WriteLine("double형 최대" + double.MaxValue);  //E+308
            Console.WriteLine("double형 최소" + double.MinValue);
            Console.WriteLine("char형 최대" + char.MaxValue);  //캐릭터 문자라서
            Console.WriteLine("char형 최소" + char.MinValue);
            */

            /*
            for(char i=char.MinValue; i<char.MaxValue; i++)
            {
                Console.Write(i);  
            }  //문자표로 만들 수 있음 리눅스에서 돌리면 다 나오는데 윈도우라서 ??가 나옴
            */

            /*
            char i1 = '최';
            char i2 = '지';
            char i3 = '연';
            Console.WriteLine((int) i1 + " " + (int)i2 + " " + (int)i3);
            */

            /*
            // Literal 리터럴 
            int i_int = 100;
            long i_lng = 100L;
            double i_dbl = 100.0;
            float i_flt = 100.0F;
            char i_chr = 'A';

            i_dbl = i_flt = i_lng = i_int = i_chr;   //표현가능한 범위가 얼만큼 크냐가 중요
            // 자료형의 표현 크기 (암묵적 형변환 가능) Type Casting
            i_dbl = i_flt = i_lng = i_int = i_chr;
            */

            /*
            string strInt = "50";
            string strLong = "20000000000"; // 200억
            string strDouble = "50.0";
            string strFloat = "50.0";
            string strString = "ABCDE";

            try
            {
                Console.WriteLine(int.Parse(strInt));
                Console.WriteLine(long.Parse(strLong));
                Console.WriteLine(double.Parse(strDouble));
                Console.WriteLine(float.Parse(strFloat));
                Console.WriteLine(double.Parse(strString));  //무조건 예외발생
            }
            catch (System.FormatException e)
            {
                Console.WriteLine("형식 에러 발생!");
                Console.WriteLine(e.Message);
            }
            catch (System.Exception e)
            {
                Console.WriteLine(e.Message);
            }
            */

            bool trueOrFalse = true;
           Console.WriteLine( trueOrFalse.ToString());  //출력시 첫문자가 대문자로 바뀜

            int a = 1999;
            Console.WriteLine("" + a);

            char c = 'a';
            string c2 = "" + c;
            Console.WriteLine(c2);  //문자열 + 문자는 잘 나옴
            
            
 ```
