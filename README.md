- 👋 Hi, I’m @KiranMurade
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
KiranMurade/KiranMurade is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

package stringProgram;

public class Program11 {
	public static void main(String[] args) {
		String s1 = "siddesh jalgaonkar the universe boss";
		 
		String[] s2 = s1.split(" ");
		
		for(int i=0; i<= s2.length-1; i++) {
		//System.out.println(s2[i].length());
		String str = s2[i];
		System.out.println(str.substring(0,1).toUpperCase() + str.substring(1,str.length()));
		}
		//System.out.println(s2[1].length());
		//System.out.println(s2[2].length());
		//System.out.println(s2[3].length());
	}

}
