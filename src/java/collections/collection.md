## Collection

Collection interface provides all basic methods to manipulate groups of objects

| Method                                        | Description                                                         |
|-----------------------------------------------|---------------------------------------------------------------------|
| boolean add(E e)                              | Element insertion                                                   |
| boolean addAll(Collection<? extends E> c)     | Insert all elements from other collection                           |
| boolean remove(E e)                           | Element deletion                                                    |
| boolean removeAll(Collection<?> c)            | Remove all elements that are also contained in specified collection |
| boolean removeIF(Predicate<? super E> filter) | Remove all elements that stisfy specified predicate                 |
| boolean retainAll(Collection<?> c)            | Remove all elements except those contained in specifeid collections |
| int size()                                    | Total number of elements                                            |
| void clear()                                  | Clears the collection                                               |
| boolean contains(Object e)                    | Search for an object                                                |

Collection is extended by following interfaces:
- [List](list.md)
- [Queue](queue.md)
- [Set](set.md)