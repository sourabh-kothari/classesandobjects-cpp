# classesandobjects-cpp


// Write your Student class here
class Student
{
    public:
    int scores[100],i;
    public:
    void input()
    {
        for(i=0;i<5;i++)
        {
            cin>>scores[i];
        }
    }
        public:
        int calculateTotalScore()
        {int sum=0;
            for(i=0;i<5;i++)
            {
                sum=sum+scores[i];
                 }     return(sum);
            
        }
};

