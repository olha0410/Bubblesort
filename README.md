public int[] bubblesort (int[] list){
  for (i=0; i<list.length; i++){
    for (k=0; k<list.length; i++){
      if (list[k] > list[k+1]){
        storage = list[k];
        list[k] = list[k+1];
        list[k+1] = storage;
      }
    }
  }
