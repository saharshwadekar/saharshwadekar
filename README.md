### Hi there 👋

<!--
**saharshwadekar/saharshwadekar** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

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
            return "Striving to embrace the limitless possibilities of technology,
                    I aim to be at the forefront of innovation,
                    shaping a future where the only constant is boundless progress.";
        }

};
```
