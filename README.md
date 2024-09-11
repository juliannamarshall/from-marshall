# My name is Julianna Marshall
###### My favorite sport is golf

I like playing **golf** because it is a sport that you can play for a **lifetime**.<br>I have been playing golf since 2018.

---

### Three people who play golf
1. Tiger Woods
2. Rory McIlroy
3. William Marshall (My Dad)

### Places you can play golf
- Golf Course
- Top Golf
- Golf Simulator

---

### Restaurants
| Name of Restaurant | Why I recommend it | Location |
| --- | --- | --- |
| Pancho's Mexican Grill | Big portion sizes for cheap | Blue Springs, MO |
| Mr. Sushi | Sushi Restaurant and Hibachi all in one | Lee's Summit, MO |
| Neptune Bakery | Delicious Custard and Baked goods | Jersey City, NJ |
| McDonalds | Cheap and Quick Fast Food | Maryville, MO |

---

### Jokes
> The worst thing about prison was the dementors. 

*Michael Scott*

> When life gives you lemonade, make lemos. Life will be all like What?? 

*Phil Dunphy*

---

### Code Fencing
This code snippet gets the value of an object with an interface.
~~~
interface MyInterface {
  id: number;
  name: string;
  properties: string[];
}

const myObject: MyInterface = {
  id: 1,
  name: 'foo',
  properties: ['a', 'b', 'c']
};

function getValue(value: keyof MyInterface) {
  return myObject[value];
}

getValue('id'); // 1
getValue('count')
~~~
[Link to snippet source](https://code.pieces.app/collections/typescript)


[Link to MyDish.md](MyDish.md)