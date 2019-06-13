
### Less-Terrible std::visit

`std::visit`, with the need for user-defined `overloaded` operators to be remotely useful, is frankly horrible. 

### `enum class` stringification

A clean way to convert a enum class to the string representation of the values would be nice.
(I mostly want this to make python interfaces nicer. Having to hand roll switch-cases for every enum class I'm passing through an interface is annoying)

### Better `std::tuple`

`std::pair` is nice with `val.first`, `val.second`. `std::get<n>(tup)` is gross. Why doesn't std::tuple support first, second, third ... ninth at least? 

I'd imagine the lion's share of std::tuple usage is for tuples with less then nine items.
