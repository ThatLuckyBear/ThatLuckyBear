Just a list to keep track of Markdown stuff that I'd like to use/remember

using collapsible menus in markdown: https://stackoverflow.com/questions/77822788/nested-indented-lists-with-collapsable-sections

- <details open>
  <summary><a href="#">Section 1 with a link</a></summary>

  - <details>
    <summary><a href="../src/actions/">subsection 2 with a link</a></summary>

    - a list
    - with some stuff

    > and other things

    - [x] like
    - [ ] a task list 

    </details>

  - <details>
    <summary><b>another subsection</a></summary>

    a. with another list
    b. and some other stuff
    d. [and](),
      [more](),
      [classic](),
      [md]
    e. _no need_ __of html__
    </details>

  - <details>
    <summary>last sub-section</a></summary>

    blablabla

    ```rb
    def some_code
      puts "Rails is so cool"
    end
    ```
    </details>

  - a random not collapsable section
    > legacy. Should be restructured.

    ```js
    console.log("look what I found, a new js framework. Still no real alternative to rails though")
    ```

  - <details>
    <summary>and another collapsable section</summary>

    ...
  </details>

- <details>
  <summary>section 2</summary>
      
  some parent content

  and another list

  - <details>
    <summary>section 2.1</summary>

      and some content
    </details>

  - <details>
    <summary>section 2.2</summary>

      and some content
    </details>
  
  - section 2.3
    and some no collapsed content

</details>
