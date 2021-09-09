# assignment2-TIRUMALAREDDY
# Hitesh Reddy TirumalaReddy
## Hyderabad
Hyderabad is a city which is located in **telangana** and it gives us great **opportunity** for students.In Hyderabad they are **wide range of tech industries**.

****
## Traveling from Maryville to your Hyderabad

1. First, I booked flight ticket from maryville to hyderabad via,chicago to delhi to hyderabad . 
   1. I booked a rented car from maryville to kansas airport.
2. After reaching the airport the flight was delay and I waited in kansas for 5 hours.
3. Finally i checked into my flight and i reached in chicago .After reaching in chicago aiport.The airport was so huge and I spent some quality time in the aiport.
4. I checkin to my flight to delhi.After reaching to delhi there is a connect flight to hyderabad.
5. when I reach hyderabad i felt so happy because it is one of my favorite place.


- I brougth some gifts to my relatives and for my family as well .
- I have presented iphone13 to my brother and watch to father and mother  they felt so happy.

Take me to [AboutMe](AboutMe.md)

---
## Beverage Section
List of Beverages in kFC, location and price table

| Drink	| Location | Price   |
| ------| -------- | --------|
| PEPSI	| KFC      | $2.00   |
| SPRITE| KFC      | $1.50   |
| LIMCA | KFC      | $1.00   |
| SODA  | KFC      | $1.10   |

---

---
## Pithy Quotes

As Albert Einstein said:

> “Two things are infinite: the universe and human stupidity I'm not sure about the universe.”

>Be who you are and say what you feel, because those who mind don't matter, and those who matter don't mind.”

---

### Code Fencing

*Treap Merge operation* 

> Because a Cartesian tree is a binary tree, it is natural to use it as a binary search tree for an ordered sequence of values. 
> This idea was applied by Seidel & Aragon (1996), who suggested the use of random numbers as priorities. The data structure resulting from this random choice is called a treap. 
> (t,r) combines two subtrees t and r and returns the new tree. This operation also has O(logN) complexity. 
> It works under the assumption that t and r are ordered. Thus, we need to combine these trees without violating the order of priorities. To do this, we choose as the root the tree which has higher priority in the root node, and recursively call Merge for the other tree and the corresponding subtree of the selected root node.

Treap Merge Operation [Reference_link](https://en.wikipedia.org/wiki/Cartesian_tree)

code for Treap Merge operation

      void merge (pitem & t,pitem l,pitem r)
      {
      if (!l || !r)
      t = l ? l : r;
      else if (l->prior > r->prior)
      merge (l->r, l->r, r),  t = l;
      else
      merge (r->l, l, r->l),  t = r;
      }




Treap Merge Operation [Code_link](https://cp-algorithms.com/data_structures/treap.html)