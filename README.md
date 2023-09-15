![github template](https://github.com/saharshwadekar/saharshwadekar/assets/99036174/93f43ca3-fe3b-4992-98b1-e70185c91b8e)



```cpp
class AboutMe
{
    private:
        string MyName;
        int MyAge;

    public:
        AboutMe(string name = "Saharsh Wadekar" , int age = 21): MyName(name),MyAge(age) {}
        virtual ~AboutMe() {}

        vector<vector<string>> getMyPreciousSkills(void){
            vector<string> languages = {"C", "C++", "PHP", "Python"};
            vector<string> webTechnologies = {"HTML5", "CSS3"};
            vector<string> dataScienceTool = {"NumPy", "Pandas", "Matplotlib"};
            vector<string> currentFocus = {"Data Science", "AI", "Machine Learning"};

            return {languages, webTechnologies, dataScienceTool, currentFocus};
        }

        string getMyFutureGoal(void){
            return "Striving to embrace the limitless possibilities of technology, I aim to be at the forefront of innovation, shaping a future where the only constant is boundless progress.";
        }

};
```
  
