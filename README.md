# MissionReadyHQ-Mission5

public class MissionFiveApexClass 
{
    public static void dingDongList() 
    {
        //Declares a List “input” to hold 4 numbers: 12, 20, 30, 17
        List<Integer> input = new List<Integer>();
        
        input.add(12); 
        input.add(20); 
        input.add(30); 
        input.add(17); 
        
        //Loop through “input”
        for(integer i:input)
        {
            //If i divisible by 3 == 'Ding'
            if((math.mod(i, 3)==0) && (math.mod(i, 5)!=0))
            {
              system.debug('Ding');
            }
            //If divisible by 5 == Dong
            else if((math.mod(i, 5)==0) && (math.mod(i, 3)!=0))
            {
              system.debug('Dong');  
            }
            //If divisible by both 3 & 5 == DingDong
            else if((math.mod(i, 3)==0) && (math.mod(i, 5)==0))
            {
             system.debug('DingDong'); 
            }
            //If divisible by neither == 17
            else
            {
             system.debug(17); 
            }
        }
        
    }
}
