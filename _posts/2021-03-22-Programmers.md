---
layout: post
categories : [programmers, Algorithm]
title: "Study Java Skills as Programmers"
date: 2020-03-22
excerpt: "성장 일기"
tags: [java, programmers, test, study, everyday, Algorithm]
comments: true
---


## 1

```
public class lev_1test {
	//소수갯수구하기
	class Solution {
	    public int solution(int n) {
	        int answer = 0;
	        int i = 2; // i : 나눌 대상
	        boolean isPrime=true;
	        while(i<=n){
	            isPrime=true;
	            for(int num=2;num<i;num++){
	                if(i%num==0){
	                    isPrime=false;
	                    break;
	                }
	                
	            }
	            if(isPrime==true){
	                answer++;
	            }
	            i++;
	        }
	        return answer;
	    }
	  
	}
	class Solution2 {
		//입력받은 문자열 크기별로 재배치 대문자는 뒤로
	    public String solution(String s) {
	        char[] arr = s.toCharArray();
	        for(int i=1;i<arr.length;i++){
	            for(int j=0;j<arr.length;j++){
	                if(arr[i]>arr[j]){
	                    char temp=arr[j];
	                    arr[j]=arr[i];
	                    arr[i]=temp;
	                    i--;
	                    break;
	                }
	            }
	        }
	        return new String(arr);
	}
}
}

```

## 애로사항
* ..

# 느낀점
* 내용이 너무 허전하다...
* 내일은 좀더 어려운걸로!

