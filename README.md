#include<stdio.h> //multiway decision use by switch statement
void main()
{
    int week;
    printf("enter week day");
    scanf("%d",& week);

switch (week)
{
    case 0: printf("mon");break;
     case 1: printf("Tue");break;
      case 2: printf("Wed");break;
       case 3: printf("thr");break;
        case 4: printf("fri");break;
         case 5: printf("sat");break;
          case 6: printf("sun");break;
           default: printf("invalid input ");
    
}
}
   
