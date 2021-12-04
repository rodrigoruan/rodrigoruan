## Hello, my name is Rodrigo Ruan! :nerd_face:

I'm a software engineer, currently studying Node and Flutter.

I'm studying web development at @trybe and CS at @UAM.

I love writing codes and my skills are
<br/>
JavaScript, React, React Native, Redux, CSS3, HTML5, Git, MongoDB, Node, Bootstrap, MySQL, Python and C++.

My hobbies are watching animes (berserk is the best!) and studying competitive programming.
You can see my solved problems at:
<br/>

<a href="https://www.codewars.com/users/rodrigo%20ruan">Codewars</a> |
<a href="https://www.beecrowd.com.br/judge/pt/profile/544334">URI Online Judge</a> |
<a href="https://www.codingame.com/profile/72398efce9e8fff752e10af0f47415381021524">CodinGame</a> |
<a href="https://codeforces.com/profile/rodrigoruan16">Codeforces</a>

Some utils:

Binary Search:
```bash
#include <bits/stdc++.h>

using namespace std;

int main(vector<int>& nums, int target) {
  int L = 0, R = nums.size() - 1;
  while (L <= R) {
    int mid = L + (R - L) / 2;
    if(nums[mid] == target) return mid;
    if(nums[mid] < target) L = mid + 1;
    else R = mid - 1;
  }
  return -1;
}
```

Bubble Sort:
```bash
#include <bits/stdc++.h>

using namespace std;

vector<int> solution(vector<int> nums) {
  for(int i = 0; i < nums.size(); i++) {
    for(int j = 0; j < nums.size(); j++) {
      if(nums[i] < nums[j]) {
        int temp = nums[j];
        nums[j] = nums[i];
        nums[i] = temp;
      }
    }
  }
  return nums;
}
```

If you want to contact me.
<br/>
[LinkedIn](https://www.linkedin.com/in/rodrigo-ruan/) |
[Gmail](mailto:rodrigopython16@gmail.com)
