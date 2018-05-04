#Exercise I

  a. O(n^3)

  b. O(n)

  c. O(n)

  d. O(n^2)

  e. O(n^3)

  f. O(1);

  g. O(n log n)

#Exercise II

  a. 
  ```
    let j = arr.length;
    let res;
    for(let i = 0; i <= arr.length-1; i++) {
      res = arr[j] > arr[i] ? arr[j] : arr[i];
    }
  ```

  b. This is Psuedo Code
  ```
  Start with the number of stories
    Divide the number of stories by two
    drop an egg
      if ( !egg breaks ) divide top half and go to middle
        drop an egg
        if (egg breaks) divide bottom half of top and drop
        else continue until you find the floor the egg breaks at
      else go to middle of bottom half, drop egg
        if ( egg breaks ) divide bottom half and go to middle
        else continue until egg breaks
        return
  ```

#Exercise III
  
  a. O(n), You end up having to iterate through every element because partitioning is wasted.

  b. O(n log n), I honestly don't know specifically, but I believe it has to do with how small it ends up breaking the the problem down. It also has to do with Quicksorts ability to deal with partially sorted number in that it can skip some operations if it is already sorted. Honestly this is kind of an educated guess.

