1. Java stack Deque, ArrayQueue, peek, pop, push, size,isEmpty
1. StringBuilder, reverse, append
1. ArrayList add(not append!), Arrays.asList,
2. String length, indexOf, lastIndexOf, toCharArray, valueOf, String.join(" ", words), compareTo
3. Character.getNumericValue, isLetter, isLetterOrDigit, toUpperCase, isWhitespace, use cast int to get ascii value, use cash (char) to character from int value,
4. Integer.parseInt,
5. Collections.reverse, Collections.sort, Collections.max
6. List to array, .stream().toArray(new String[0]), result.toArray(new int[result.size()][]); myNewStream.toArray(String[]::new);  
   List of integer to array: result.stream().mapToInt(Integer::intValue).toArray();
8. Queue, LinkedList, peek, poll, offer
9. Deque addFirst as push of Stack, removeFirst as pop of Stack, peek as top
10. Arrays, copyOf, copyRangeOf, clone, System.arraycopy, Arrays.sort, Comparator.reverseOrder,
    1. Arrays.asList() Returns a fixed-size list backed by the specified array.
12. HashMap containsKey, remove, keySet, values, entrySet,
13. PriorityQueue, poll, offer,
    1. To initialize an array list with priorty queue: new ArrayList<Point>(maxHeap);
    2. To add a list of elements: addAll
15. Collections
   1. Convert String[] array to list, use Arrays.asList()
   2. Convert List<String> to array, use list.toArray(new String[size]), or list.toStream().toArray(String[]::new) in java 8, or list.toArray(String[]::new) in java 11
   3. Covert List<int[]> to array int[][], list.toArray(new int[size][]), list.toArray(new int[][]{}), or list.stream().toArray(int[][]::new) in java 8, or list.toArray(int[][]::new) in java 11
   4. Convert a list of Characters to a string using str.stream()  
                            .map(String::valueOf)  
                            .collect(Collectors.joining());  
1. ArrayDeque doens't allow Null while LinkedList allows Null
1. Hashmap putIfAbsent
   1. convert Collections of List<String> of hash map values to list, new ArrayList<>(values())
3. String repleat(java 11), String.join("", Collections.nCopies(n, s))(java 8),
   1. new String(charArray)
1. Iterator  
       for (Iterator<String> it = names.iterator(); it.hasNext();) {
        String name = it.next();
        System.out.println(name);
    }   
## Multi threading
1. There are two ways to create a thread:
   1. By extending Thread class
   1. By implementing Runnable interface.
1. What is difference between user Thread and daemon Thread?  
   When we create a Thread in java program, it’s known as user thread. A daemon thread runs in background and doesn’t prevent JVM from terminating. When there are no user threads running, JVM shutdown the program and quits. A child thread created from daemon thread is also a daemon thread.
1. What is context switching?  
   In Context switching the state of the process (or thread) is stored so that it can be restored and execution can be resumed from the same point later. Context switching enables the multiple processes to share the same CPU.
1. Describe the purpose and working of sleep() method.  
   The sleep() method in java is used to block a thread for a particular time, which means it pause the execution of a thread for a specific time. 
