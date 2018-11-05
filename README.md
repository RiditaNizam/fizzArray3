public int[] fizzArray3(int start, int end) {
  
  int[] answerArray = new int[end - start];
  
  for(int i = 0; i < answerArray.length; i++){
    answerArray[i] = start + i;
  }
  
  return answerArray;
  
}
