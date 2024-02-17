![GithubBackgournd](https://github.com/saharshwadekar/saharshwadekar/assets/99036174/66acab80-6ba6-4ac8-b9ed-f8a117e1f605)
```cpp
class AboutMe
{
    private:
        string MyName;
        int MyAge;
        

    public:
        AboutMe(string name = "Saharsh Wadekar" , int age = 21): MyName(name),MyAge(age) {}
        virtual ~AboutMe() {}

        void greetEveryOne(void)
        {
            string greetingMSG = "Very Warm WELCOME TO MY LOBBY.";
            cout << greetingMSG << endl;
        }![GithubBackgournd](https://github.com/saharshwadekar/saharshwadekar/assets/99036174/bdbdbb1b-294d-40ab-bc51-0002bd2efb95)

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
