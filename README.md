<!-- TOC -->

- [CSS/SCSS/SASS](#cssscsssass)
- [Javascript](#javascript)
  - [React](#react)
  - [Jest](#jest)
- [Markdown](#markdown)
- [Java](#java)
- [PHP](#php)
  - [WordPress](#wordpress)
- [Elixir](#elixir)
- [Global](#global)

<!-- /TOC -->

### CSS/SCSS/SASS

- `bb`
    ```css
    box-sizing: border-box;
    ```

### Javascript/Typescript

- `cl`
    ```js
    console.log(#);
    ```
- `tc`
    ```js
    try {
    } catch(err) {
        console.log('Error', err);
    }
    ```
- `rp`
    ```js
    return new Promise((resolve, reject) => {
    });
    ```
- `ep`
    ```js
    export
    ```
- `err`
    ```js
    const error = new Error('#')
    error.response = {}
    ```

#### React
- `re`
    ```js
    import React from 'react';
    ```

#### Jest

- `des`
    ```js
    describe('#', () => {
    });
    ```
- `di`
    ```js
    describe('#', () => {
        it('#', () => {
        });
    });
    ```
- `ddi`
    ```js
    describe('#', () => {
        describe('#', () => {
            it('#', () => {
            });
        });
    });
    ```
- `each`
    ```js
    it.each([
      ['#', #],
    ])('%s', (name, #) => {
    })
    ```
- `it`
    ```js
    it('#', () => {
    });
    ```

### Markdown

- `badge`
    ```md
    ![](https://img.shields.io/badge/#-#-#.svg)
    ```
    
    - `bs`
        
        ![](https://img.shields.io/badge/css-bootstrap-5F2C7C.svg)

    - `materialize`

        ![](https://img.shields.io/badge/css-materialize-F95972.svg)

    - `sass`

        ![](https://img.shields.io/badge/css_preprocessor-sass-DC4497.svg)

    - `pg`

        ![](https://img.shields.io/badge/data-postgres-316391.svg)

    - `jq`

        ![](https://img.shields.io/badge/jquery-version-005FAD.svg)
        
    - `node`
        
        ![](https://img.shields.io/badge/node-version-61BC62.svg)

    - `lo`
        
        ![](https://img.shields.io/badge/lodash-version-3554FF.svg)

    - `ng`
        
        ![](https://img.shields.io/badge/angularJS-version-D00027.svg)
    
    - `gr`

        ![](https://img.shields.io/badge/grunt-version-ED8024.svg)

    - `hb`

        ![](https://img.shields.io/badge/handlebars-version-F47904.svg)
    
    - `ch`

        ![](https://img.shields.io/badge/testing-chai+mocha-a40802.svg)

### Java

- `main`
    ```java
    public static void main(String[] args) {
        #
    }
    ```

- `out`
    ```java
    System.out.println(#);
    ```

- `bi`
    ```java
    BigInteger
    ```

- `mmtest`
    ```java
	@Test
	public void test_#_expect#() throws Exception {
	    mockMvc.perform(
            #("/#")
                .contentType(MediaType.APPLICATION_JSON_UTF8)
		)
            .andExpect(status().#());
	}
    ```

- `psf`
    ```java
    public static final
    ```

- `pv`
    ```java
    public void 
    ```

### PHP

#### WordPress

- `db`
    ```php
    define( 'WP_DEBUG', true );
    define( 'WP_DEBUG_LOG', true );
    define( 'WP_DEBUG_DISPLAY', false )
    ```

### Elixir

- `iex`
    ```elixir
    require IEx
    IEx.pry()
    ```

### Global

- `gitignore`
    ```
    **/node_modules/
    **/.env
    **/.vscode
    **/.DS_Store
    **/.listin
    ```