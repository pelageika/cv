## **Pelageya Chursina**
#### **Contact information:**
**Phone:** +375296685400

**E-mail:** pelageika81@gmail.com;
            pelageika18@gmail.com
            
**Telegram:** @CHPelageya        

### **Briefly About Myself:**

I am responsible, proactive, stress-resistant, sociable, honest. My strengths are good managerial and leadership skills, customer focus, systems thinking, positive attitude. I like to study, I always strive to learn something new.

### **Skills and Proficency:**

- HTML, C++
- Word, Excel, Access
- Adobe Photoshop, Blender, Inkscape

### **Code example:**     

#include<iostream>


class circle {
	
protected:
	double R;
	
public:
	circle(double R) {
		this->R = R;
	
	}

	double get_R() {
		return R;
	}

	double Area() {
		return 3.14*R*R;
	}
};

class ring: public circle {
	double r;
public:
	ring(double R, double r) : circle(R) {
		this->r = r;
	}

	double Area() {
		return 3.14*(R*R - r*r);
	}
};

using namespace std;


int main() {
	double x, y;
	cin >> x >> y;
	circle c(x);
	cout << c.Area();
	cout << endl;
	ring r(x, y);
	cout << r.Area();
	system("pause");
	return 0;
}

### **Project:**
	
	cv

