1. Java stack Deque, ArrayQueue, peek, pop, push, size,isEmpty
1. StringBuilder, reverse, append
1. ArrayList add(not append!), Arrays.asList,
2. String length, indexOf, lastIndexOf, toCharArray, valueOf, String.join(" ", words),
3. Character.getNumericValue, isLetter, isLetterOrDigit, toUpperCase, isWhitespace, use cast int to get ascii value, use cash (char) to character from int value,
4. Integer.parseInt,
5. Collections.reverse, Collections.sort,
6. List to array, .stream().toArray(new String[0]), result.toArray(new int[result.size()][]); myNewStream.toArray(String[]::new);
7. Queue, LinkedList, peek, poll, offer
8. Deque addFirst as push of Stack, removeFirst as pop of Stack, peek as top
9. Arrays, copyOf, copyRangeOf, clone, System.arraycopy, Arrays.sort, Comparator.reverseOrder, 
10. HashMap containsKey, remove, keySet, values, entrySet,
11. PriorityQueue, poll, offer
12. 
## Multi threading
1. There are two ways to create a thread:
   1. By extending Thread class
   1. By implementing Runnable interface.
1. What is difference between user Thread and daemon Thread?  
   When we create a Thread in java program, it’s known as user thread. A daemon thread runs in background and doesn’t prevent JVM from terminating. When there are no user threads running, JVM shutdown the program and quits. A child thread created from daemon thread is also a daemon thread.
