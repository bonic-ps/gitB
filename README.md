# gitB
second sample repo for testing

Now B has made some changes to general's file.
I am in the space waiting for some meteors to shower over me.
Once I get the meteors I will come back and 
give it to you. Thanku general for the support.


I am back general. Lets start our research.
Make me the CEO general!!!

Or else I wont go to space again!!!

Well I changed my mind general please let me stay here!

class Solution {
    increment(arr,n){
        //code here
        for(let i=arr.length-1;i>=0;i--){
            arr[i]++
            if(arr[i]>9){
                arr[i]=0
            }else{
                return arr
            }
        }
        
         arr.unshift(1)
         return arr
    }
}

for (let i = n - 1; i >= 0; i--) {
            if (arr[i] <= 8) {
                arr[i] = arr[i] + 1;
                return arr;
            } else {
                arr[i] = 0;
            }
        }
        arr.unshift(1);
        return arr;
    }
}

// function reverser(a){
//     let word = "";  let ans = "";
//     for(let i=0; i<a.length; i++){
//         word += a[i];
//         if(a[i] === " "){
//             ans += word.split("").reverse().join("");
//             word = "";
//         }
//     }
//     return ans;
// }

// console.log(reverser(str));


let arr = [0] ;  
arr[arr.length-1] += 1;

for(let i = arr.length-1; i>=0; i--){
    if(arr[i] < 10){
        break;
    }  // arr[i] = 10
    let [ld, rd] = arr[i].toString().split('').map(e => Number(e));
    arr[i] = rd;
    if(arr[i-1] != undefined) {    // ld = 1;  rd = 0
      arr[i-1] += ld;  // 3
    }
    else{
        arr.unshift(ld);
    }
}
console.log(arr);


This is the solution for the second question.
Thanku for listening the session.
https://10x-react-frontend.netlify.app/

langchain
Deepinlearning.AI