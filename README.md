![](https://img.shields.io/badge/Microverse-blueviolet)

# Advanced Building Blocks - Bubble Sort

[Collaborative project]
>In this project, we will implement the bubble sort algorithm. The assignment is focused on the use of yield and passing a block to a method.

>The next part of the assignment is similar to the previous method, but it accepts code blocks using yield.

## Built With

- Ruby

## Prerequest

Ruby instaled.

## How to use instructions

- Bubble Sort [buble_sort.rb] — buble_sort method accept one argument(array)
  
  To test code you can provide following line at the and of the code

  ```ruby
  p bubble_sort([4, 3, 78, 2, 0, 2])
  ```
  
  and then run from terminal
  
  ```terminal
  foo:$ ruby bubble_sort.rb
  ```

- in this case, it receives a block of code and uses yield in method to execute the descending sort
  
  To test the code, you can provide the following line at the end of the code.

  ```ruby
  sorted_by_array = bubble_sort_by(%w[hi hello hey]) do |left, right|
    left.length - right.length
  end

  p sorted_by_array
  ```
  
  and then run from terminal
  
  ```terminal
  foo:$ ruby bubble_sort_by.rb
  ```

## Authors

👤 **Marijan Brvar**
![Marijan's GitHub stats](https://github-readme-stats.vercel.app/api?username=marijanbrvar&count_private=true&theme=dark&show_icons=true)

- GitHub: [@githubhandle](https://github.com/marijanbrvar)
- Twitter: [@twitterhandle](https://twitter.com/marijanbrvar)
- LinkedIn: [LinkedIn](https://linkedin.com/in/marijanbrvar)

👤 **Tanzila**

- GitHub: [@githubhandle](https://github.com/tanzila-abedin)
- Twitter: [@twitterhandle](https://twitter.com/TanzilaAbedin)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/tanzila-abedin-331440b2/)

## 📝 License

This project is [MIT](LICENSE) licensed.
