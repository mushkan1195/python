**What is frozen sets?** ​

            A frozen sets is an immutable version of a sets in python set.​

            It stores unique elements.​

            Elements cannot be modified after creation.​

            It supports most set operations like **union**, **intersection**, etc.​

```​
  Syntax ​

            Frozenset(iterable)​

  Example :​

            Fs = frozenset([1 ,2, 3])​
            
            print(fs)​

  Output:​

        Frozenset({1, 2, 3})​

```
**MAIN FEATURES OF FROZEN SETS**

            **Immutable** :**You cannot add or remove elements.** ​
            
            **Stores only unique value** : Duplicate values are automatically removed.​
            
            **Unordered collection**​
            
            **Hashable** : It can be used as dictionary keys or elements inside another set.​
            
            Supports set operation​


**Advantages of frozen sets​**
            Prevents accidental changes​
            
            Secure for constant data​
            
            Supports mathematical set operation​
            
            Can be used as dictionary keys ​
            
            Useful in nested sets ​

**Limitation of frozen sets​**

            Cannot add elements ​
            
            Cannot remove elements​
            
            Less flexible than normal sets​
            
            Method not supported:​
            
            * Add()​
            
            * Remove()​
            
            * Update()​
            ​​
