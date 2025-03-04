```cpp
class Himanshu {
  private:
    string name, college, degree, strength;
    vector<string> languages_spoken;
  
  public:
    Himanshu() {  
        name = "Himanshu Raj";
        college = "Indian Institute of Technology, Bombay";
        degree = "B.Tech. in Metallurgical Engineering and Materials Science";
        strength = "Strong hold in DS Algo and MERN Stack Web Development";
        languages_spoken = {"English", "Hindi"};
    }
    
    void current_status() {
        cout << "I am a third-year student at " << college 
             << " pursuing " << degree << endl;
    }

    void say_bye() {
        cout << "Thanks for dropping by. How did you find my work? Interesting?" << endl;
    }
};
