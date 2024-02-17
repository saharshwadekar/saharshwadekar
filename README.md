
![LinkedInBackground1](https://github.com/saharshwadekar/saharshwadekar/assets/99036174/8a83f3b0-8f71-452a-9e77-6a9eec399895)



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
  
