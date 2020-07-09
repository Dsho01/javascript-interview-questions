# JavaScript Interview Questions & Answers

> Click :star:if you like the project. Pull Request are highly appreciated. Follow me [@SudheerJonna](https://twitter.com/SudheerJonna) for technical updates.

Go to [Coding Exercise](#coding-exercise) for coding specific questions

## Downloading PDF/Epub formats

You can download the PDF and Epub version of this repository from the latest run on the [actions tab](https://github.com/sudheerj/JavaScript-Interview-Questions/actions).

---

## Disclaimer

The questions provided in this repository are the summary of frequently asked questions across numerous companies. We cannot guarantee that these questions will actually be asked during your interview process, nor should you focus on memorizing all of them. The primary purpose is for you to get a sense of what some companies might ask — do not get discouraged if you don't know the answer to all of them ⁠— that is ok!

Good luck with your interview 😊

---

### Table of Contents

| No. | Questions |
|---- | ---------
|1  | [What are the possible ways to create objects in JavaScript?](#what-are-the-possible-ways-to-create-objects-in-javascript) |
|2  | [What is prototype chain?](#what-is-prototype-chain)|
|3  | [What is the difference between Call, Apply and Bind?](#what-is-the-difference-between-call-apply-and-bind)|
|4  | [What is JSON and its common operations](#what-is-json-and-its-common-operations)|
|5  | [What is the purpose of array slice method?](#what-is-the-purpose-of-array-slice-method)|
|6  | [What is the purpose of array splice method?](#what-is-the-purpose-of-array-splice-method)|
|7  | [What is the difference between slice and splice?](#what-is-the-difference-between-slice-and-splice)|
|8  | [How do you compare Object and Map?](#how-do-you-compare-object-and-map)|
|9  | [What is the difference between == and === operators?](#what-is-the-difference-between-==-and-===-operators)|
|10 | [What are lambda or arrow functions?](#what-are-lambda-or-arrow-functions)|
|11 | [What is a first class function?](#what-is-a-first-class-function)|
|12 | [What is a first order function?](#what-is-a-first-order-function)|
|13 | [What is a higher order function?](#what-is-a-higher-order-function)|
|14 | [What is a unary function?](#what-is-a-unary-function)|
|15 | [What is currying function?](#what-is-currying-function)|
|16 | [What is a pure function?](#what-is-a-pure-function)|
|17 | [What is the purpose of let keyword?](#what-is-the-purpose-of-let-keyword)|
|18 | [What is the difference between let and var?](#what-is-the-difference-between-let-and-var)|
|19 | [What is the reason to choose the name let as keyword?](#what-is-the-reason-to-choose-the-name-let-as-keyword)|
|20 | [How do you redeclare variables in switch block without an error?](#how-do-you-redeclare-variables-in-switch-block-without-an-error)|
|21 | [What is Temporal Dead Zone?](#what-is-temporal-dead-zone)|
|22 | [What is IIFE(Immediately Invoked Function Expression)?](#what-is-iife-(-immediately-invoked-function-expression-)-)|
|23 | [What is the benefit of using modules?](#what-is-the-benefit-of-using-modules)|
|24 | [What is memoization?](#what-is-memoization)|
|25 | [What is Hoisting?](#what-is-hoisting)|
|26 | [What are classes in ES6?](#what-are-classes-in-es6)|
|27 | [What are closures?](#what-are-closures)|
|28 | [What are modules?](#what-are-modules)|
|29 | [Why do you need modules?](#why-do-you-need-modules)|
|30 | [What is scope in javascript?](#what-is-scope-in-javascript)|
|31 | [What is a service worker?](#what-is-a-service-worker)|
|32 | [How do you manipulate DOM using service worker?](#how-do-you-manipulate-dom-using-service-worker)|
|33 | [How do you reuse information across service worker restarts?](#how-do-you-reuse-information-across-service-worker-restarts)|
|34 | [What is IndexedDB?](#what-is-indexeddb)|
|35 | [What is web storage?](#what-is-web-storage)|
|36 | [What is a post message?](#what-is-a-post-message)|
|37 | [What is a cookie?](#what-is-a-cookie)|
|38 | [Why do you need a Cookie?](#why-do-you-need-a-cookie)|
|39 | [What are the options in a cookie?](#what-are-the-options-in-a-cookie)|
|40 | [How do you delete a cookie?](#how-do-you-delete-a-cookie)|
|41 | [What are the differences between cookie, local storage and session storage?](#What-are-the-differences-between-cookie,-local-storage-and-session-storage)|
|42 | [What is the main difference between localStorage and sessionStorage?](#what-is-the-main-difference-between-localstorage-and-sessionstorage)|
|43 | [How do you access web storage?](#how-do-you-access-web-storage)|
|44 | [What are the methods available on session storage?](#what-are-the-methods-available-on-session-storage)|
|45 | [What is a storage event and its event handler?](#what-is-a-storage-event-and-its-event-handler)|
|46 | [Why do you need web storage?](#why-do-you-need-web-storage)|
|47 | [How do you check web storage browser support?](#how-do-you-check-web-storage-browser-support)|
|48 | [How do you check web workers browser support?](#how-do-you-check-web-workers-browser-support)|
|49 | [Give an example of web worker?](#give-an-example-of-web-worker)|
|50 | [What are the restrictions of web workers on DOM?](#what-are-the-restrictions-of-web-workers-on-dom)|
|51 | [What is a promise?](#what-is-a-promise)|
|52 | [Why do you need a promise?](#why-do-you-need-a-promise)|
|53 | [What are the three states of promise?](#what-are-the-three-states-of-promise)|
|54 | [What is a callback function?](#what-is-a-callback-function)|
|55 | [Why do we need callbacks?](#why-do-we-need-callbacks)|
|56 | [What is a callback hell?](#what-is-a-callback-hell)|
|57 | [What is server-sent events?](#what-is-server-sent-events)|
|58 | [How do you receive server-sent event notifications?](#how-do-you-receive-server-sent-event-notifications)|
|59 | [How do you check browser support for server-sent events?](#how-do-you-check-browser-support-for-server-sent-events)|
|60 | [What are the events available for server sent events?](#what-are-the-events-available-for-server-sent-events)|
|61 | [What are the main rules of promise?](#what-are-the-main-rules-of-promise)|
|62 | [What is callback in callback?](#what-is-callback-in-callback)|
|63 | [What is promise chaining?](#what-is-promise-chaining)|
|64 | [What is promise.all](#what-is-promise.all)|
|65 | [What is the purpose of race method in promise?](#what-is-the-purpose-of-race-method-in-promise)|
|66 | [What is a strict mode in javascript?](#what-is-a-strict-mode-in-javascript)|
|67 | [Why do you need strict mode?](#why-do-you-need-strict-mode)|
|68 | [How do you declare strict mode?](#how-do-you-declare-strict-mode)|
|69 | [What is the purpose of double exclamation?](#what-is-the-purpose-of-double-exclamation)|
|70 | [What is the purpose of delete operator?](#what-is-the-purpose-of-delete-operator)|
|71 | [What is typeof operator?](#what-is-typeof-operator)|
|72 | [What is undefined property?](#what-is-undefined-property)|
|73 | [What is null value?](#what-is-null-value)|
|74 | [What is the difference between null and undefined?](#what-is-the-difference-between-null-and-undefined)|
|75 | [What is eval?](#What-is-eval)|
|76 | [What is the difference between window and document?](#what-is-the-difference-between-window-and-document)|
|77 | [How do you access history in javascript?](#how-do-you-access-history-in-javascript)|
|78 | [What are the javascript data types?](#what-are-the-javascript-data-types)|
|79 | [What is isNaN?](#what-is-isnan)|
|80 | [What are the differences between undeclared and undefined variables?](#what-are-the-differences-between-undeclared-and-undefined-variables)|
|81 | [What are global variables?](#what-are-global-variables)|
|82 | [What are the problems with global variables?](#what-are-the-problems-with-global-variables)|
|83 | [What is NaN property?](#what-is-nan-property)|
|84 | [What is the purpose of isFinite function?](#what-is-the-purpose-of-isfinite-function)
|85 | [What is an event flow?](#what-is-an-event-flow)|
|86 | [What is event bubbling?](#what-is-event-bubbling)|
|87 | [What is event capturing?](#what-is-event-capturing)|
|88 | [How do you submit a form using JavaScript?](#how-do-you-submit-a-form-using-javascript)|
|89 | [How do you find operating system details?](#how-do-you-find-operating-system-details)|
|90 | [What is the difference between document load and DOMContentLoaded events?](#what-is-the-difference-between-document-load-and-domcontentloaded-events)|
|91 | [What is the difference between native, host and user objects?](#what-is-the-difference-between-native,-host-and-user-objects)|
|92 | [What are the tools or techniques used for debugging JavaScript code?](#what-are-the-tools-or-techniques-used-for-debugging-javascript-code)|
|93 | [What are the pros and cons of promises over callbacks?](#what-are-the-pros-and-cons-of-promises-over-callbacks)|
|94 | [What is the difference between an attribute and a property?](#what-is-the-difference-between-an-attribute-and-a-property)|
|95 | [What is same-origin policy?](#what-is-same-origin-policy)|
|96 | [What is the purpose of void 0?](#what-is-the-purpose-of-void-0)|
|97 | [Is JavaScript a compiled or interpreted language?](#is-javascript-a-compiled-or-interpreted-language)|
|98 | [Is JavaScript a case-sensitive language?](#is-javascript-a-case-sensitive-language)|
|99 | [Is there any relation between Java and JavaScript?](#is-there-any-relation-between-java-and-javascript)|
|100| [What are events?](#what-are-events)|
|101| [Who created javascript?](#who-created-javascript)|
|102| [What is the use of preventDefault method?](#what-is-the-use-of-preventdefault-method)|
|103| [What is the use of stopPropagation method?](#what-is-the-use-of-stoppropagation-method)|
|104| [What are the steps involved in return false?](#what-are-the-steps-involved-in-return-false)|
|105| [What is BOM?](#what-is-bom)|
|106| [What is the use of setTimeout?](#what-is-the-use-of-settimeout)|
|107| [What is the use of setInterval?](#what-is-the-use-of-setinterval)|
|108| [Why is JavaScript treated as Single threaded?](#why-is-javascript-treated-as-single-threaded)|
|109| [What is an event delegation?](#what-is-an-event-delegation)|
|110| [What is ECMAScript?](#what-is-ecmascript)|
|111| [What is JSON?](#what-is-json)|
|112| [What are the syntax rules of JSON?](#what-are-the-syntax-rules-of-json)|
|113| [What is the purpose JSON stringify?](#what-is-the-purpose-json-stringify)|
|114| [How do you parse JSON string?](#how-do-you-parse-json-string)|
|115| [Why do you need JSON?](#why-do-you-need-json)|
|116| [What are PWAs?](#what-are-pwas?)|
|117| [What is the purpose of clearTimeout method?](#what-is-the-purpose-of-cleartimeout-method)|
|118| [What is the purpose of clearInterval method?](#what-is-the-purpose-of-clearinterval-method)|
|119| [How do you redirect new page in javascript?](#how-do-you-redirect-new-page-in-javascript)|
|120| [How do you check whether a string contains a substring?](#how-do-you-check-whether-a-string-contains-a-substring)|
|121| [How do you validate an email in javascript?](#how-do-you-validate-an-email-in-javascript)|
|122| [How do you get the current url with javascript?](#how-do-you-get-the-current-url-with-javascript)|
|123| [What are the various url properties of location object?](#what-are-the-various-url-properties-of-location-object)|
|124| [How do get query string values in javascript?](#how-do-get-query-string-values-in-javascript)|
|125| [How do you check if a key exists in an object?](#how-do-you-check-if-a-key-exists-in-an-object)|
|126| [How do you loop through or enumerate javascript object?](#how-do-you-loop-through-or-enumerate-javascript-object)|
|127| [How do you test for an empty object?](#how-do-you-test-for-an-empty-object)|
|128| [What is an arguments object?](#what-is-an-arguments-object)|
|129| [How do you make first letter of the string in an uppercase?](#how-do-you-make-first-letter-of-the-string-in-an-uppercase)|
|130| [What are the pros and cons of for loop?](#what-are-the-pros-and-cons-of-for-loop)|
|131| [How do you display the current date in javascript?](#how-do-you-display-the-current-date-in-javascript)|
|132| [How do you compare two date objects?](#how-do-you-compare-two-date-objects)|
|133| [How do you check if a string starts with another string?](#how-do-you-check-if-a-string-starts-with-another-string)|
|134| [How do you trim a string in javascript?](#how-do-you-trim-a-string-in-javascript)|
|135| [How do you add a key value pair in javascript?](#how-do-you-add-a-key-value-pair-in-javascript)|
|136| [Is the '!--' notation represents a special operator?](#is-the-'!--'-notation-represents-a-special-operator)|
|137| [How do you assign default values to variables?](#how-do-you-assign-default-values-to-variables)|
|138| [How do you define multiline strings?](#how-do-you-define-multiline-strings)|
|139| [What is an app shell model?](#what-is-an-app-shell-model)|
|140| [Can we define properties for functions?](#can-we-define-properties-for-functions)|
|141| [What is the way to find the number of parameters expected by a function?](#what-is-the-way-to-find-the-number-of-parameters-expected-by-a-function)|
|142| [What is a polyfill?](#what-is-a-polyfill)|
|143| [What are break and continue statements?](#what-are-break-and-continue-statements)|
|144| [What are js labels?](#what-are-js-labels)|
|145| [What are the benefits of keeping declarations at the top?](#what-are-the-benefits-of-keeping-declarations-at-the-top)|
|146| [What are the benefits of initializing variables?](#what-are-the-benefits-of-initializing-variables)|
|147| [What are the recommendations to create new object?](#what-are-the-recommendations-to-create-new-object)|
|148| [How do you define JSON arrays?](#how-do-you-define-json-arrays)|
|149| [How do you generate random integers?](#how-do-you-generate-random-integers)|
|150| [Can you write a random integers function to print integers with in a range?](#can-you-write-a-random-integers-function-to-print-integers-with-in-a-range)|
|151| [What is tree shaking?](#what-is-tree-shaking)|
|152| [What is the need of tree shaking?](#what-is-the-need-of-tree-shaking)|
|153| [Is it recommended to use eval?](#is-it-recommended-to-use-eval)|
|154| [What is a Regular Expression?](#what-is-a-regular-expression)|
|155| [What are the string methods available in Regular expression?](#what-are-the-string-methods-available-in-regular-expression)|
|156| [What are modifiers in regular expression?](#what-are-modifiers-in-regular-expression)|
|157| [What are regular expression patterns?](#what-are-regular-expression-patterns)|
|158| [What is a RegExp object?](#what-is-a-regexp-object)|
|159| [How do you search a string for a pattern?](#how-do-you-search-a-string-for-a-pattern)|
|160| [What is the purpose of exec method?](#what-is-the-purpose-of-exec-method)|
|161| [How do you change style of a HTML element?](#how-do-you-change-style-of-a-html-element)|
|162| [What would be the result of 1+2+'3'?](#what-would-be-the-result-of-1+2+'3')|
|163| [What is a debugger statement?](#what-is-a-debugger-statement)|
|164| [What is the purpose of breakpoints in debugging?](#what-is-the-purpose-of-breakpoints-indebugging)|
|165| [Can I use reserved words as identifiers?](#can-i-use-reserved-words-as-identifiers)|
|166| [How do you detect a mobile browser?](#how-do-you-detect-a-mobile-browser)|
|167| [How do you detect a mobile browser without regexp?](#how-do-you-detect-a-mobile-browser-without-regexp)|
|168| [How do you get the image width and height using JS?](#how-do-you-get-the-image-width-and-height-using-js)|
|169| [How do you make synchronous HTTP request?](#how-do-you-make-synchronous-http-request)|
|170| [How do you make asynchronous HTTP request?](#how-do-you-make-asynchronous-http-request)|
|171| [How do you convert date to another timezone in javascript?](#how-do-you-convert-date-to-another-timezone-in-javascript)|
|172| [What are the properties used to get size of window?](#what-are-the-properties-used-to-get-size-of-window)|
|173| [What is a conditional operator in javascript?](#what-is-a-conditional-operator-in-javascript)|
|174| [Can you apply chaining on conditional operator?](#Can-you-apply-chaining-on-conditional-operator)|
|175| [What are the ways to execute javascript after page load?](#what-are-the-ways-to-execute-javascript-after-page-load)|
|176| [What is the difference between proto and prototype?](#what-is-the-difference-between-proto-and-prototype)|
|177| [Give an example where do you really need semicolon?](#give-an-example-where-do-you-really-need-semicolon)|
|178| [What is a freeze method?](#what-is-a-freeze-method)|
|179| [What is the purpose of freeze method?](#what-is-the-purpose-of-freeze-method)|
|180| [Why do I need to use freeze method?](#why-do-i-need-to-use-freeze-method)|
|181| [How do you detect a browser language preference?](#how-do-you-detect-a-browser-language-preference)|
|182| [How to convert string to title case with javascript?](#how-to-convert-string-to-title-case-with-javascript)|
|183| [How do you detect javascript disabled in the page?](#how-do-you-detect-javascript-disabled-in-the-page)|
|184| [What are various operators supported by javascript?](#what-are-various-operators-supported-by-javascript)|
|185| [What is a rest parameter?](#what-is-a-rest-parameter)|
|186| [What happens if you do not use rest parameter as a last argument?](#what-happens-if-you-do-not-use-rest-parameter-as-a-last-argument)|
|187| [What are the bitwise operators available in javascript?](#what-are-the-bitwise-operators-available-in-javascript)|
|188| [What is a spread operator?](#what-is-a-spread-operator)|
|189| [How do you determine whether object is frozen or not?](#how-do-you-determine-whether-object-is-frozen-or-not)|
|190| [How do you determine two values same or not using object?](#how-do-you-determine-two-values-same-or-not-using-object)|
|191| [What is the purpose of using object is method?](#what-is-the-purpose-of-using-object-is-method)|
|192| [How do you copy properties from one object to other?](#how-do-you-copy-properties-from-one-object-to-other)|
|193| [What are the applications of assign method?](#what-are-the-applications-of-assign-method)|
|194| [What is a proxy object?](#what-is-a-proxy-object)|
|195| [What is the purpose of seal method?](#what-is-the-purpose-of-seal-method)|
|196| [What are the applications of seal method?](#what-are-the-applications-of-seal-method)|
|197| [What are the differences between freeze and seal methods?](#what-are-the-differences-between-freeze-and-seal-methods)|
|198| [How do you determine if an object is sealed or not?](#how-do-you-determine-if-an-object-is-sealed-or-not)|
|199| [How do you get enumerable key and value pairs?](#how-do-you-get-enumerable-key-and-value-pairs)|
|200| [What is the main difference between Object.values and Object.entries method?](#what-is-the-main-difference-between-object.values-and-object.entries-method)|
|201| [How can you get the list of keys of any object?](#how-can-you-get-the-list-of-keys-of-any-object)|
|202| [How do you create an object with prototype?](#how-do-you-create-an-object-with-prototype)|
|203| [What is a WeakSet?](#what-is-a-weakset)|
|204| [What are the differences between WeakSet and Set?](#what-are-the-differences-between-weakset-and-set)|
|205| [List down the collection of methods available on WeakSet?](#list-down-the-collection-of-methods-available-on-weakset)|
|206| [What is a WeakMap?](#what-is-a-weakmap)|
|207| [What are the differences between WeakMap and Map?](#what-are-the-differences-between-weakmap-and-map)|
|208| [List down the collection of methods available on WeakMap?](#list-down-the-collection-of-methods-available-on-weakmap)|
|209| [What is the purpose of uneval?](#what-is-the-purpose-of-uneval)|
|210| [How do you encode an URL?](#how-do-you-encode-an-url)|
|211| [How do you decode an URL?](#how-do-you-decode-an-url)|
|212| [How do you print the contents of web page?](#how-do-you-print-the-contents-of-web-page)|
|213| [What is the difference between uneval and eval?](#what-is-the-difference-between-uneval-and-eval)|
|214| [What is an anonymous function?](#what-is-an-anonymous-function)|
|215| [What is the precedence order between local and global variables?](#what-is-the-precedence-order-between-local-and-global-variables)|
|216| [What are javascript accessors?](#what-are-javascript-accessors)|
|217| [How do you define property on Object constructor?](#how-do-you-define-property-on-object-constructor)|
|218| [What is the difference between get and defineProperty?](#what-is-the-difference-between-get-and-defineproperty)|
|219| [What are the advantages of Getters and Setters?](#what-are-the-advantages-of-getters-and-setters)|
|220| [Can I add getters and setters using defineProperty method?](#can-i-add-getters-and-setters-using-defineproperty-method)|
|221| [What is the purpose of switch-case?](#what-is-the-purpose-of-switch-case)|
|222| [What are the conventions to be followed for the usage of swtich case?](#what-are-the-conventions-to-be-followed-for-the-usage-of-swtich-case)|
|223| [What are primitive data types?](#what-are-primitive-data-types)|
|224| [What are the different ways to access object properties?](#what-are-the-different-ways-to-access-object-properties)|
|225| [What are the function parameter rules?](#what-are-the-function-parameter-rules)|
|226| [What is an error object?](#what-is-an-error-object)|
|227| [When you get a syntax error?](#when-you-get-a-syntax-error)|
|228| [What are the different error names from error object?](#what-are-the-different-error-names-from-error-object)|
|229| [What are the various statements in error handling?](#what-are-the-various-statements-in-error-handling)|
|230| [What are the two types of loops in javascript?](#what-are-the-two-types-of-loops-in-javascript)|
|231| [What is nodejs?](#what-is-nodejs)|
|232| [What is an Intl object?](#what-is-an-intl-object)|
|233| [How do you perform language specific date and time formatting?](#how-do-you-perform-language-specific-date-and-time-formatting)|
|234| [What is an Iterator?](#what-is-an-iterator)|
|235| [How does synchronous iteration works?](#how-does-synchronous-iteration-works)|
|235| [What is an event loop?](#what-is-an-event-loop)|
|236| [What is call stack?](#what-is-call-stack)|
|237| [What is an event queue?](#what-is-an-event-queue)|
|238| [What is a decorator?](#what-is-a-decorator)|
|239| [What are the properties of Intl object?](#what-are-the-properties-of-intl-object)|
|240| [What is an Unary operator?](#what-is-an-unary-operator)|
|241| [How do you sort elements in an array?](#how-do-you-sort-elements-in-an-array)|
|242| [What is the purpose of compareFunction while sorting arrays?](#what-is-the-purpose-of-comparefunction-while-sorting-arrays)|
|243| [How do you reversing an array?](#how-do-you-reversing-an-array)|
|244| [How do you find min and max value in an array?](#how-do-you-find-min-and-max-value-in-an-array)|
|245| [How do you find min and max values without Math functions?](#how-do-you-find-min-and-max-values-without--math-functions)|
|246| [What is an empty statement and purpose of it?](#what-is-an-empty-statement-and-purpose-of-it)|
|247| [How do you get meta data of a module?](#how-do-you-get-meta-data-of-a-module)|
|248| [What is a comma operator?](#what-is-a-comma-operator)|
|249| [What is the advantage of a comma operator?](#what-is-the-advantage-of-a-comma-operator)|
|250| [What is typescript?](#what-is-typescript)|
|251| [What are the differences between javascript and typescript?](#what-are-the-differences-between-javascript-and-typescript)|
|252| [What are the advantages of typescript over javascript?](#what-are-the-advantages-of-typescript-over-javascript)|
|253| [What is an object initializer?](#what-is-an-object-initializer)|
|254| [What is a constructor method?](#what-is-a-constructor-method)|
|255| [What happens if you write constructor more than once in a class?](#what-happens-if-you-write-constructor-more-than-once-in-a-class)|
|256| [How do you call the constructor of a parent class?](#how-do-you-call-the-constructor-of-a-parent-class)|
|257| [How do you get the prototype of an object?](#how-do-you-get-the-prototype-of-an-object)|
|258| [What happens If I pass string type for getPrototype method?](#what-happens-if-i-pass-string-type-for-getprototype-method)|
|259| [How do you set prototype of one object to another?](#how-do-you-set-prototype-of-one-object-to-another)|
|260| [How do you check whether an object can be extendable or not?](#how-do-you-check-whether-an-object-can-be-extendable-or-not)|
|261| [How do you prevent an object to extend?](#how-do-you-prevent-an-object-to-extend)|
|262| [What are the different ways to make an object non-extensible?](#what-are-the-different-ways-to-make-an-object-non-extensible)|
|263| [How do you define multiple properties on an object?](#how-do-you-define-multiple-properties-on-an-object)|
|264| [What is MEAN in javascript?](#what-is-mean-in-javascript)|
|265| [What Is Obfuscation in javascript?](#what-is-obfuscation-in-javascript)|
|266| [Why do you need Obfuscation?](#why-do-you-need-obfuscation)|
|267| [What is Minification?](#what-is-minification)|
|268| [What are the advantages of minification?](#what-are-the-advantages-of-minification)|
|269| [What are the differences between Obfuscation and Encryption?](#what-are-the-differences-between-obfuscation-and-encryption)|
|270| [What are the common tools used for minification?](#what-are-the-common-tools-used-for-minification)|
|271| [How do you perform form validation using javascript?](#how-do-you-perform-form-validation-using-javascript)|
|272| [How do you perform form validation without javascript?](#how-do-you-perform-form-validation-without-javascript)|
|273| [What are the DOM methods available for constraint validation?](#what-are-the-dom-methods-available-for-constraint-validation)|
|274| [What are the available constraint validation DOM properties?](#what-are-the-available-constraint-validation-dom-properties)|
|275| [What are the list of validity properties?](#what-are-the-list-of-validity-properties)|
|276| [Give an example usage of rangeOverflow property?](#give-an-example-usage-of-rangeoverflow-property)|
|277| [Is enums feature available in javascript?](#is-enums-feature-available-in-javascript)|
|278| [What is an enum?](#What-is-an-enum)|
|279| [How do you list all properties of an object?](#how-do-you-list-all-properties-of-an-object)|
|280| [How do you get property descriptors of an object?](#how-do-you-get-property-descriptors-of-an-object)|
|281| [What are the attributes provided by a property descriptor?](#what-are-the-attributes-provided-by-a-property-descriptor)|
|282| [How do you extend classes?](#how-do-you-extend-classes)|
|283| [How do I modify the url without reloading the page?](#how-do-i-modify-the-url-without-reloading-the-page)|
|284| [How do you check whether an array includes a particular value or not?](#how-do-you-check-whether-an-array-includes-a-particular-value-or-not)|
|285| [How do you compare scalar arrays?](#how-do-you-compare-scalar-arrays)|
|286| [How to get the value from get parameters?](#how-to-get-the-value-from-get-parameters)|
|287| [How do you print numbers with commas as thousand separators?](#how-do-you-print-numbers-with-commas-as-thousand-separators)|
|288| [What is the difference between java and javascript?](#what-is-the-difference-between-java-and-javascript)|
|289| [Is javascript supports namespace?](#is-javascript-supports-namespace)|
|290| [How do you declare namespace?](#how-do-you-declare-namespace)|
|291| [How do you invoke javascript code in an iframe from parent page?](#how-do-you-invoke-javascript-code-in-an-iframe-from-parent-page)|
|292| [How do get the timezone offset from date?](#how-do-get-the-timezone-offset-from-date)|
|293| [How do you load CSS and JS files dynamically?](#how-do-you-load-css-and-js-files-dynamically)|
|294| [What are the different methods to find HTML elements in DOM?](#what-are-the-different-methods-to-find-html-elements-in-dom)|
|295| [What is jQuery?](#what-is-jquery)|
|296| [What is V8 JavaScript engine?](#what-is-v8-javascript-engine)|
|297| [Why do we call javascript as dynamic language?](#why-do-we-call-javascript-as-dynamic-language)|
|298| [What is a void operator?](#what-is-a-void-operator)|
|299| [How to set the cursor to wait?](#how-to-set-the-cursor-to-wait)|
|300| [How do you create an infinite loop?](#how-do-you-create-an-infinite-loop)|
|301| [Why do you need to avoid with statement?](#why-do-you-need-to-avoid-with-statement)|
|302| [What is the output of below for loops?](#what-is-the-output-of-below-for-loops)|
|303| [List down some of the features of ES6?](#list-down-some-of-the-features-of-es6)|
|304| [What is ES6?](#what-is-es6)|
|305| [Can I redeclare let and const variables?](#can-I-redeclare-let-and-const-variables)|
|306| [Is const variable makes the value immutable?](#is-const-variable-makes-the-value-immutable)|
|307| [What are default parameters?](#what-are-default-parameters)|
|308| [What are template literals?](#what-are-template-literals)|
|309| [How do you write multi-line strings in template literals?](#how-do-you-write-multi-line-strings-in-template-literals)|
|310| [What are nesting templates?](#what-are-nesting-templates)|
|311| [What are tagged templates?](#what-are-tagged-templates)|
|312| [What are raw strings?](#what-are-raw-strings)|
|313| [What is destructuring assignment?](#what-is-destructuring-assignment)|
|314| [What are default values in destructuring assignment?](#what-are-default-values-in-destructuring-assignment)|
|315| [How do you swap variables in destructuring assignment?](#how-do-you-swap-variables-in-destructuring-assignment)|
|316| [What are enhanced object literals?](#what-are-enhanced-object-literals)|
|317| [What are dynamic imports?](#what-are-dynamic-imports)|
|318| [What are the use cases for dynamic imports?](#what-are-the-use-cases-for-dynamic-imports)|
|319| [What are typed arrays?](#what-are-typed-arrays)|
|320| [What are the advantages of module loaders?](#what-are-the-advantages-of-module-loaders)|
|321| [What is collation?](#what-is-collation)|
|322| [What is for...of statement?](#what-is-for...of-statement)|
|323| [What is the output of below spread operator array?](#what-is-the-output-of-below-spread-operator-array)|
|324| [Is PostMessage secure?](#is-postmessage-secure)|
|325| [What are the problems with postmessage target origin as wildcard?](#what-are-the-problems-with-postmessage-target-origin-as-wildcard)|
|326| [How do you avoid receiving postMessages from attackers?](#how-do-you-avoid-receiving-postmessages-from-attackers)|
|327| [Can I avoid using postMessages completely?](#can-i-avoid-using-postmessages-completely)|
|328| [Is postMessages synchronous?](#is-postmessages-synchronous)|
|329| [What paradigm is Javascript?](#what-paradigm-is-javascript)|
|330| [What is the difference between internal and external javascript?](#what-is-the-difference-between-internal-and-external-javascript)|
|331| [Is JavaScript faster than server side script?](#is-javascript-faster-than-server-side-script)|
|332| [How do you get the status of a checkbox?](#how-do-you-get-the-status-of-a-checkbox)|
|333| [What is the purpose of double tilde operator?](#what-is-the-purpose-of-double-tilde-operator)|
|334| [How do you convert character to ASCII code?](#how-do-you-convert-character-to-ascii-code)|
|335| [What is ArrayBuffer?](#what-is-arraybuffer)|
|336| [What is the output of below string expression?](#what-is-the-output-of-below-string-expression)|
|337| [What is the purpose of Error object?](#what-is-the-purpose-of-error-object)|
|338| [What is the purpose of EvalError object?](#what-is-the-purpose-of-evalerror-object)|
|339| [What are the list of cases error thrown from non-strict mode to strict mode?](#what-are-the-list-of-cases-error-thrown-from-non-strict-mode-to-strict-mode)|
|340| [Is all objects have prototypes?](#is-all-objects-have-prototypes)|
|341| [What is the difference between a parameter and an argument?](#what-is-the-difference-between-a-parameter-and-an-argument)|
|342| [What is the purpose of some method in arrays?](#what-is-the-purpose-of-some-method-in-arrays)|
|343| [How do you combine two or more arrays?](#how-do-you-combine-two-or-more-arrays)|
|344| [What is the difference between Shallow and Deep copy?](#what-is-the-difference-between-shallow-and-deep-copy)|
|345| [How do you create specific number of copies of a string?](#how-do-you-create-specific-number-of-copies-of-a-string)|
|346| [How do you return all matching strings against a regular expression?](#how-do-you-return-all-matching-strings-against-a-regular-expression)|
|347| [How do you trim a string at the beginning or ending?](#how-do-you-trim-a-string-at-the-beginning-or-ending)|
|348| [What is the output of below console statement with unary operator?](#what-is-the-output-of-below-console-statement-with-unary-operator)|
|349| [Does javascript uses mixins?](#does-javascript-uses-mixins)|
|350| [What is a thunk function?](#what-is-a-thunk-function)|
|351| [What are asynchronous thunks?](#what-are-asynchronous-thunks)|
|352| [What is the output of below function calls?](#what-is-the-output-of-below-function-calls)|
|353| [How to remove all line breaks from a string?](#how-to-remove-all-line-breaks-from-a-string)|
|354| [What is the difference between reflow and repaint?](#what-is-the-difference-between-reflow-and-repaint)|
|355| [What happens with negating an array?](#what-happens-with-negating-an-array)|
|356| [What happens if we add two arrays?](#what-happens-if-we-add-two-arrays)|
|357| [What is the output of prepend additive operator on falsy values?](#what-is-the-output-of-prepend-additive-operator-on-falsy-values)|
|358| [How do you create self string using special characters?](#how-do-you-create-self-string-using-special-characters)|
|358| [How do you remove falsy values from an array?](#how-do-you-remove-falsy-values-from-an-array)|
|359| [How do you get unique values of an array?](#how-do-you-get-unique-values-of-an-array)|
|360| [What is destructuring aliases?](#what-is-destructuring-aliases)|
|361| [How do you map the array values without using map method?](#how-do-you-map-the-array-values-without-using-map-method)|
|362| [How do you empty an array?](#how-do-you-empty-an-array)|
|363| [How do you rounding numbers to certain decimals](#how-do-you-rounding-numbers-to-certain-decimals)|
|364| [What is the easiest way to convert an array to an object?](#what-is-the-easiest-way-to-convert-an-array-to-an-object)|
|365| [How do you create an array with some data?](#how-do-you-create-an-array-with-some-data)|
|366| [What are the placeholders from console object?](#what-are-the-placeholders-from-console-object)|
|367| [Is it possible to add CSS to console messages?](#is-it-possible-to-add-css-to-console-messages)|
|368| [What is the purpose of dir method of console object?](#what-is-the-purpose-of-dir-method-of-console-object)|
|369| [Is it possible to debug HTML elements in console?](#is-it-possible-to-debug-html-elements-in-console)|
|370| [How do you display data in a tabular format using console object?](#how-do-you-display-data-in-a-tabular-format-using-console-object)|
|371| [How do you verify that an argument is a Number or not?](#how-do-you-verify-that-an-argument-is-a-number-or-not)|
|372| [How do you create copy to clipboard button?](#how-do-you-create-copy-to-clipboard-button)|
|373| [What is the shortcut to get timestamp?](#what-is-the-shortcut-to-get-timestamp)|
|374| [How do you flattening multi dimensional arrays?](#how-do-you-flattening-multi-dimensional-arrays)|
|375| [What is the easiest multi condition checking?](#what-is-the-easiest-multi-condition-checking)|
|376| [How do you capture browser back button?](#how-do-you-capture-browser-back-button)|
|377| [How do you disable right click in the web page?](#how-do-you-disable-right-click-in-the-web-page)|
|378| [What are wrapper objects?](#what-are-wrapper-objects)|
|379| [What is AJAX?](#what-is-ajax)|
|380| [What are the different ways to deal with Asynchronous Code?](#what-are-the-different-ways-to-deal-with-asynchronous-code)|
|381| [How to cancel a fetch request?](#how-to-cancel-a-fetch-request)|
|382| [What is web speech API?](#what-is-web-speech-api)|
|383| [What is minimum timeout throttling?](#what-is-minimum-timeout-throttling)|
|384| [How do you implement zero timeout in modern browsers?](#how-do-you-implement-zero-timeout-in-modern-browsers)|
|385| [What are tasks in event loop?](#what-are-tasks-in-event-loop)|
|386| [What are microtasks?](#what-are-microtasks)|
|387| [What are different event loops?](#what-are-different-event-loops)|
|388| [What is the purpose of queueMicrotask?](#what-is-the-purpose-of-queuemicrotask)|
|389| [How do you use javascript libraries in typescript file?](#how-do-you-use-javascript-libraries-in-typescript-file)|
|390| [What are the differences between promises and observables?](#what-are-the-differences-between-promises-and-observables)|
|391| [What is heap?](#what-is-heap)|
|392| [What is an event table?](#what-is-an-event-table)|
|393| [What is a microTask queue?](#what-is-a-microtask-queue)|
|394| [What is the difference between shim and polyfill?](#what-is-the-difference-between-shim-and-polyfill)|
|395| [How do you detect primitive or non primitive value type?](#how-do-you-detect-primitive-or-non-primitive-value-type)|
|396| [What is babel?](#what-is-babel)|
|397| [Is Node.js completely single threaded?](#is-node.js-completely-single-threaded)|
|398| [What are the common use cases of observables?](#what-are-the-common-use-cases-of-observables)|
|399| [What is RxJS?](#what-is-rxjs)|
|400| [What is the difference between Function constructor and function declaration?](#what-is-the-difference-between-function-constructor-and-function-declaration)|
|401| [What is a Short circuit condition?](#what-is-a-short-circuit-condition)|
|402| [What is the easiest way to resize an array?](#what-is-the-easiest-way-to-resize-an-array)|
|403| [What is an observable?](#what-is-an-observable)|
|404| [What is the difference between function and class declarations?](#what-is-the-difference-between-function-and-class-declarations)|
|405| [What is an async function?](#what-is-an-async-function)|
|406| [How do you prevent promises swallowing errors?](#how-do-you-prevent-promises-swallowing-errors)|
|407| [What is deno?](#what-is-deno)|
|408| [How do you make an object iterable in javascript?](#how-do-you-make-an-object-iterable-in-javascript)|
|409| [What is a Proper Tail Call?](#what-is-a-proper-tail-call)|
|410| [How do you check an object is a promise or not?](#how-do-you-check-an-object-is-a-promise-or-not)|
|411| [How to detect if a function is called as constructor?](#how-to-detect-if-a-function-is-called-as-constructor)|

1. ### What are the possible ways to create objects in JavaScript?

    There are many ways to create objects in javascript as below,


     5. **Function constructor with prototype:**
         This is similar to function constructor but it uses prototype for their properties and methods,

        ```javascript
        function Person(){}
        Person.prototype.name = "Sudheer";
        var object = new Person();
        ```

        This is equivalent to an instance created with an object create method with a function prototype and then call that function with an instance and parameters as arguments.
        ```javascript
        function func {};

        new func(x, y, z);

        **(OR)**

        // Create a new instance using function prototype.
        var newInstance = Object.create(func.prototype)

        // Call the function
        var result = func.call(newInstance, x, y, z),

        // If the result is a non-null object then use it otherwise just use the new instance.
        console.log(result && typeof result === 'object' ? result : newInstance);
        ```

    7. **Singleton pattern:**
        A Singleton is an object which can only be instantiated one time. Repeated calls to its constructor return the same instance and this way one can ensure that they don't accidentally create multiple instances.
        ```javascript
        var object = new function(){
          this.name = "Sudheer";
        }
        ```

    **[⬆ Back to Top](#table-of-contents)**

2. ### What is prototype chain?

    **Prototype chaining** is used to build new types of objects based on existing ones. It is similar to inheritance in a class based language. The prototype on object instance is available through **Object.getPrototypeOf(object)** or __proto__ property whereas prototype on constructors function is available through object.prototype.

    ![Screenshot](images/prototype_chain.png)

    **[⬆ Back to Top](#table-of-contents)**

3. ### What is the difference between Call, Apply and Bind?
    The difference between Call, Apply and Bind can be explained with below examples,

    **Call:** The call() method invokes a function with a given `this` value and arguments provided one by one
    ```javascript
    var employee1 = {firstName: 'John', lastName: 'Rodson'};
    var employee2 = {firstName: 'Jimmy', lastName: 'Baily'};

    function invite(greeting1, greeting2) {
        console.log(greeting1 + ' ' + this.firstName + ' ' + this.lastName+ ', '+ greeting2);
    }

    invite.call(employee1, 'Hello', 'How are you?'); // Hello John Rodson, How are you?
    invite.call(employee2, 'Hello', 'How are you?'); // Hello Jimmy Baily, How are you?
    ```
    **Apply:** Invokes the function and allows you to pass in arguments as an array
    ```javascript
    var employee1 = {firstName: 'John', lastName: 'Rodson'};
    var employee2 = {firstName: 'Jimmy', lastName: 'Baily'};

    function invite(greeting1, greeting2) {
        console.log(greeting1 + ' ' + this.firstName + ' ' + this.lastName+ ', '+ greeting2);
    }

    invite.apply(employee1, ['Hello', 'How are you?']); // Hello John Rodson, How are you?
    invite.apply(employee2, ['Hello', 'How are you?']); // Hello Jimmy Baily, How are you?
    ```
    **bind:** returns a new function, allowing you to pass in an array and any number of arguments
    ```javascript
    var employee1 = {firstName: 'John', lastName: 'Rodson'};
    var employee2 = {firstName: 'Jimmy', lastName: 'Baily'};

    function invite(greeting1, greeting2) {
        console.log(greeting1 + ' ' + this.firstName + ' ' + this.lastName+ ', '+ greeting2);
    }

    var inviteEmployee1 = invite.bind(employee1);
    var inviteEmployee2 = invite.bind(employee2);
    inviteEmployee1('Hello', 'How are you?'); // Hello John Rodson, How are you?
    inviteEmployee2('Hello', 'How are you?'); // Hello Jimmy Baily, How are you?
    ```
    Call and apply are pretty interchangeable. Both execute the current function immediately. You need to decide whether it’s easier to send in an array or a comma separated list of arguments. You can remember by treating Call is for comma (separated list) and Apply is for Array. Whereas Bind creates a new function that will have `this` set to the first parameter passed to bind().

    **[⬆ Back to Top](#table-of-contents)**


    **[⬆ Back to Top](#table-of-contents)**

7. ### What is the difference between slice and splice?

    Some of the major difference in a tabular form

    | Slice | Splice |
    |---- | ---------
    | Doesn't modify the original array(immutable)  | Modifies the original array(mutable) |
    | Returns the subset of original array | Returns the deleted elements as array  |
    | Used to pick the elements from array | Used to insert or delete elements to/from array|

    **[⬆ Back to Top](#table-of-contents)**

8. ### How do you compare Object and Map?
    **Objects** are similar to **Maps** in that both let you set keys to values, retrieve those values, delete keys, and detect whether something is stored at a key. Due to this reason, Objects have been used as Maps historically. But there are important differences that make using a Map preferable in certain cases.

    1. The keys of an Object are Strings and Symbols, whereas they can be any value for a Map, including functions, objects, and any primitive.
    2. The keys in Map are ordered while keys added to object are not. Thus, when iterating over it, a Map object returns keys in order of insertion.
    3. You can get the size of a Map easily with the size property, while the number of properties in an Object must be determined manually.
    4. A Map is an iterable and can thus be directly iterated, whereas iterating over an Object requires obtaining its keys in some fashion and iterating over them.
    5. An Object has a prototype, so there are default keys in the map that could collide with your keys if you're not careful. As of ES5 this can be bypassed by using map = Object.create(null), but this is seldom done.
    6. A Map may perform better in scenarios involving frequent addition and removal of key pairs.

    **[⬆ Back to Top](#table-of-contents)**

9. ### What is the difference between == and === operators?

    JavaScript provides both strict(===, !==) and type-converting(==, !=) equality comparison. The strict operators takes type of variable in consideration, while non-strict operators make type correction/conversion based upon values of variables. The strict operators follow the below conditions for different types,
    1. Two strings are strictly equal when they have the same sequence of characters, same length, and same characters in corresponding positions.
    2. Two numbers are strictly equal when they are numerically equal. i.e, Having the same number value.
       There are two special cases in this,
       1. NaN is not equal to anything, including NaN.
       2. Positive and negative zeros are equal to one another.
    3. Two Boolean operands are strictly equal if both are true or both are false.
    4. Two objects are strictly equal if they refer to the same Object.
    5. Null and Undefined types are not equal with ===, but equal with ==. i.e,
        null===undefined --> false but null==undefined --> true

    Some of the example which covers the above cases,

    ```javascript
    0 == false   // true
    0 === false  // false
    1 == "1"     // true
    1 === "1"    // false
    null == undefined // true
    null === undefined // false
    '0' == false // true
    '0' === false // false
    []==[] or []===[] //false, refer different objects in memory
    {}=={} or {}==={} //false, refer different objects in memory
    ```

    **[⬆ Back to Top](#table-of-contents)**


13. ### What is a higher order function?
    Higher-order function is a function that accepts other function as an argument or returns a function as a return value.
    ```javascript
    const firstOrderFunc = () => console.log ('Hello I am a First order function');
    const higherOrder = ReturnFirstOrderFunc => ReturnFirstOrderFunc ();
    higherOrder (firstOrderFunc);
    ```

    **[⬆ Back to Top](#table-of-contents)**

16. ### (Possibly Redux) What is a pure function?

    A **Pure function** is a function where the return value is only determined by its arguments without any side effects. i.e, If you call a function with the same arguments 'n' number of times and 'n' number of places in the application then it will always return the same value. Let's take an example to see the difference between pure and impure functions,
    ```javascript
    //Impure
    let numberArray = [];
    const impureAddNumber = number => numberArray.push (number);
    //Pure
    const pureAddNumber = number => argNumberArray =>
      argNumberArray.concat ([number]);

    //Display the results
    console.log (impureAddNumber (6)); // returns 6
    console.log (numberArray); // returns [6]
    console.log (pureAddNumber (7) (numberArray)); // returns [6, 7]
    console.log (numberArray); // returns [6]
    ```
    As per above code snippets, Push function is impure itself by altering the array and returning an push number index which is independent of parameter value. Whereas Concat on the other hand takes the array and concatenates it with the other array producing a whole new array without side effects. Also, the return value is a concatenation of previous array.
    Remember that Pure functions are important as they simplify unit testing without any side effects and no need for dependency injection. They also avoid tight coupling and makes harder to break your application by not having any side effects. These principles are coming together with **Immutability** concept of ES6 by giving preference to **const** over **let** usage.

    **[⬆ Back to Top](#table-of-contents)**

17. ### What is the purpose of let keyword?

    The `let` statement declares a **block scope local variable**. Hence the variables defined with let keyword are limited in scope to the block, statement, or expression on which it is used. Whereas variables declared with the var keyword used to define a variable globally, or locally to an entire function regardless of block scope. Let's take an example to demonstrate the usage,
    ```javascript
    let counter = 30;
    if (counter === 30) {
      let counter = 31;
      console.log(counter); // 31
    }
    console.log(counter); // 30 (because if block variable won't exist here)
    ```

    **[⬆ Back to Top](#table-of-contents)**

18. ### What is the difference between let and var?
    You can list out the differences in a tabular format

    | var | let |
    |---- | ---------
    | It is been available from the beginning of JavaScript  | Introduced as part of ES6 |
    | It has function scope | It has block scope  |
    | Variables will be hoisted | Hoisted but not initialized |

    Let's take an example to see the difference,
    ```javascript
    function userDetails(username) {
       if(username) {
         console.log(salary); // undefined(due to hoisting)
         console.log(age); // error: age is not defined
         let age = 30;
         var salary = 10000;
       }
       console.log(salary); //10000 (accessible to due function scope)
       console.log(age); //error: age is not defined(due to block scope)
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

22. ### What is IIFE(Immediately Invoked Function Expression)?
    IIFE (Immediately Invoked Function Expression) is a JavaScript function that runs as soon as it is defined. The signature of it would be as below,
    ```javascript
    (function ()
        {
          // logic here
        }
     )
    ();
    ```
    The primary reason to use an IIFE is to obtain data privacy because any variables declared within the IIFE cannot be accessed by the outside world. i.e, If you try to access variables with IIFE then it throws an error as below,
    ```javascript
    (function ()
            {
              var message = "IIFE";
              console.log(message);
            }
     )
    ();
    console.log(message); //Error: message is not defined
    ```

    **[⬆ Back to Top](#table-of-contents)**

23. ### What is the benefit of using modules?
    There are a lot of benefits to using modules in favour of a sprawling. Some of the benefits are,
    1. Maintainablity
    2. Reusability
    3. Namespacing

    **[⬆ Back to Top](#table-of-contents)**

26. ### What are classes in ES6?
    In ES6, Javascript classes are primarily syntactical sugar over JavaScript’s existing prototype-based inheritance.
    For example, the prototype based inheritance written in function expression as below,
    ```javascript
    function Bike(model,color) {
        this.model = model;
        this.color = color;
    }

    Bike.prototype.getDetails = function() {
        return this.model + ' bike has' + this.color + ' color';
    };
    ```
    Whereas ES6 classes can be defined as an alternative
    ```javascript
    class Bike{
      constructor(color, model) {
        this.color= color;
        this.model= model;
      }

      getDetails() {
        return this.model + ' bike has' + this.color + ' color';
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

27. ### What are closures?
    A closure is the combination of a function and the lexical environment within which that function was declared. i.e, It is an inner function that has access to the outer or enclosing function’s variables. The closure has three scope chains
    1. Own scope where variables defined between its curly brackets
    2. Outer function’s variables
    3. Global variables
    Let's take an example of closure concept,
    ```javascript
    function Welcome(name){
      var greetingInfo = function(message){
       console.log(message+' '+name);
      }
    return greetingInfo;
    }
    var myFunction = Welcome('John');
    myFunction('Welcome '); //Output: Welcome John
    myFunction('Hello Mr.'); //output: Hello Mr.John
    ```
    As per the above code, the inner function(greetingInfo) has access to the variables in the outer function scope(Welcome) even after outer function has returned.

    **[⬆ Back to Top](#table-of-contents)**

28. ### What are modules?
    Modules refers small units of independent, reusable code and also act as foundation of many JavaScript design patterns.  Most of the JavaScript modules export an object literal, a function, or a constructor

    **[⬆ Back to Top](#table-of-contents)**

29. ### Why do you need modules?
    Below are the list of benefits using modules in javascript ecosystem
    1. Maintainablity
    2. Reusability
    3. Namespacing

    **[⬆ Back to Top](#table-of-contents)**

31. ### What is a service worker?
    A Service worker is basically a script (JavaScript file) that runs in background, separate from a web page and provide features that don't need a web page or user interaction. Some of the major features of service workers are Rich offline experiences(offline first web application development), periodic background syncs, push notifications, intercept and handle network requests and programmatically managing a cache of responses.

    **[⬆ Back to Top](#table-of-contents)**

32. ### How do you manipulate DOM using service worker?
    Service worker can't access the DOM directly. But it can communicate with the pages it controls by responding to messages sent via the `postMessage` interface, and those pages can manipulate the DOM.

    **[⬆ Back to Top](#table-of-contents)**

33. ### How do you reuse information across service worker restarts?
    The problem with service worker is that it get terminated when not in use, and restarted when it's next needed, so you cannot rely on global state within a service worker's `onfetch` and `onmessage` handlers. In this case, service workers will have access to IndexedDB API in order to persist and reuse across restarts.

    **[⬆ Back to Top](#table-of-contents)**

34. ### What is IndexedDB?
    IndexedDB is a low-level API for client-side storage of larger amounts of structured data, including files/blobs. This API uses indexes to enable high-performance searches of this data.

    **[⬆ Back to Top](#table-of-contents)**

35. ### What is web storage?
    Web storage is an API that provides a mechanism by which browsers can store key/value pairs locally within the user's browser, in a much more intuitive fashion than using cookies. The web storage provides two mechanisms for storing data on the client.
    1. **Local storage:** It stores data for current origin with no expiration date.
    2. **Session storage:** It stores data for one session and the data is lost when the browser tab is closed.

    **[⬆ Back to Top](#table-of-contents)**

36. ### What is a post message?
    Post message is a method that enables cross-origin communication between Window objects.(i.e, between a page and a pop-up that it spawned, or between a page and an iframe embedded within it). Generally, scripts on different pages are allowed to access each other if and only if the pages follow same-origin policy(i.e, pages share the same protocol, port number, and host).

    **[⬆ Back to Top](#table-of-contents)**

37. ### What is a Cookie?
    A cookie is a piece of data that is stored on your computer to be accessed by your browser. Cookies are saved as key/value pairs.
    For example, you can create a cookie named username as below,
    ```javascript
    document.cookie = "username=John";
    ```

    ![Screenshot](images/cookie.png)

    **[⬆ Back to Top](#table-of-contents)**

38. ### Why do you need a Cookie?
    Cookies are used to remember information about the user profile(such as username). It basically involves two steps,
    1. When a user visits a web page, user profile can be stored in a cookie.
    2. Next time the user visits the page, the cookie remembers user profile.

    **[⬆ Back to Top](#table-of-contents)**

39. ### What are the options in a cookie?
    There are few below options available for a cookie,
    1. By default, the cookie is deleted when the browser is closed but you can change this behavior by setting expiry date (in UTC time).
    ```javascript
    document.cookie = "username=John expires=Sat, 8 Jun 2019 12:00:00 UTC";
    ```
    2. By default, the cookie belongs to a current page. But you can tell the browser what path the cookie belongs to using a path parameter.
    ```javascript
    document.cookie = "username=John path=/services";
    ```

    **[⬆ Back to Top](#table-of-contents)**

40. ### How do you delete a cookie?
    You can delete a cookie by setting the expiry date as a passed date. You don't need to specify a cookie value in this case.
    For example, you can delete a username cookie in the current page as below.
    ```javascript
    document.cookie = "username=; expires=Fri, 07 Jun 2019 00:00:00 UTC; path=/;";
    ```
    **Note:** You should define the cookie path option to ensure that you delete the right cookie. Some browsers doesn't allow to delete a cookie unless you specify a path parameter.

    **[⬆ Back to Top](#table-of-contents)**

41. ### What are the differences between cookie, local storage and session storage?
    Below are some of the differences between cookie, local storage and session storage,

    | Feature | Cookie | Local storage | Session storage |
    |---- | --------- | ----- | ----- |
    | Accessed on client or server side | Both server-side & client-side | client-side only | client-side only |
    | Lifetime | As configured using Expires option  | until deleted | until tab is closed |
    | SSL support | Supported | Not supported | Not supported |
    | Maximum data size | 4KB | 5 MB | 5MB |

    **[⬆ Back to Top](#table-of-contents)**

42. ### What is the main difference between localStorage and sessionStorage?
    LocalStorage is same as SessionStorage but it persists the data even when the browser is closed and reopened(i.e it has no expiration time) whereas in sessionStorage data gets cleared when the page session ends.

    **[⬆ Back to Top](#table-of-contents)**

46. ### Why do you need web storage?
    Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance. Also, the information is never transferred to the server. Hence this is recommended approach than Cookies.

    **[⬆ Back to Top](#table-of-contents)**

49. ### Give an example of web worker?
    You need to follow below steps to start using web workers for counting example
    1. Create a Web Worker File:  You need to write a script to increment the count value. Let's name it as counter.js
    ```javascript
    let i = 0;

    function timedCount() {
      i = i + 1;
      postMessage(i);
      setTimeout("timedCount()",500);
    }

    timedCount();
    ```
    Here postMessage() method is used to post a message back to the HTML page
    2. Create a Web Worker Object: You can create a web worker object by checking for browser support. Let's name this file as web_worker_example.js
    ```javascript
    if (typeof(w) == "undefined") {
      w = new Worker("counter.js");
    }
    ```
    and we can receive messages from web worker
    ```javascript
    w.onmessage = function(event){
      document.getElementById("message").innerHTML = event.data;
    };
    ```
    3. Terminate a Web Worker:
    Web workers will continue to listen for messages (even after the external script is finished) until it is terminated. You can use terminate() method to terminate listening the messages.
    ```javascript
    w.terminate();
    ```
    4. Reuse the Web Worker: If you set the worker variable to undefined you can reuse the code
    ```javascript
    w = undefined;
    ```

    **[⬆ Back to Top](#table-of-contents)**

51. ### What is a promise?
    A promise is an object that may produce a single value some time in the future with either a resolved value or a reason that it’s not resolved(for example, network error). It will be in one of the 3 possible states: fulfilled, rejected, or pending.

    The syntax of Promise creation looks like below,
    ```js
        const promise = new Promise(function(resolve, reject) {
          // promise description
        })
    ```

    The usage of a promise would be as below,

    ```javascript
    const promise = new Promise(resolve => {
      setTimeout(() => {
        resolve("I'm a Promise!");
      }, 5000);
    }, reject => {

    });

    promise.then(value => console.log(value));
    ```
    The action flow of a promise will be as below,

    ![Screenshot](images/promises.png)

    **[⬆ Back to Top](#table-of-contents)**

52. ### Why do you need a promise?
    Promises are used to handle asynchronous operations. They provide an alternative approach for callbacks by reducing the callback hell and writing the cleaner code.

    **[⬆ Back to Top](#table-of-contents)**

53. ### What are the three states of promise?
    Promises have three states:
    1. **Pending:** This is an initial state of the Promise before an operation begins
    2. **Fulfilled:** This state indicates that specified operation was completed.
    3. **Rejected:** This state indicates that the operation did not complete. In this case an error value will be thrown.

    **[⬆ Back to Top](#table-of-contents)**

54. ### What is a callback function?
    A callback function is a function passed into another function as an argument. This function is invoked inside the outer function to complete an action.
    Let's take a simple example of how to use callback function
    ```javascript
    function callbackFunction(name) {
      console.log('Hello ' + name);
    }

    function outerFunction(callback) {
      let name = prompt('Please enter your name.');
      callback(name);
    }

    outerFunction(callbackFunction);
    ```
    **[⬆ Back to Top](#table-of-contents)**

55. ### Why do we need callbacks?
    The callbacks are needed because javascript is a event driven language. That means instead of waiting for a response javascript will keep executing while listening for other events.
    Let's take an example with first function invoking an API call(simulated by setTimeout) and next function which logs the message.
    ```javascript
    function firstFunction(){
      // Simulate a code delay
      setTimeout( function(){
        console.log('First function called');
      }, 1000 );
    }
    function secondFunction(){
      console.log('Second function called');
    }
    firstFunction();
    secondFunction();

    Output
    // Second function called
    // First function called
    ```
    As observed from the output, javascript didn't wait for the response of first function and remaining code block get executed. So callbacks used in a way to make sure that certain code doesn’t execute until other code finished execution.

    **[⬆ Back to Top](#table-of-contents)**

57. ### What is server-sent events?
    Server-sent events (SSE) is a server push technology enabling a browser to receive automatic updates from a server via HTTP connection without resorting to polling. These are a one way communications channel - events flow from server to client only. This is been used in Facebook/Twitter updates, stock price updates, news feeds etc.

    **[⬆ Back to Top](#table-of-contents)**

58. ### How do you receive server-sent event notifications?
    The EventSource object is used to receive server-sent event notifications. For example, you can receive messages from server as below,
    ```javascript
    if(typeof(EventSource) !== "undefined") {
      var source = new EventSource("sse_generator.js");
      source.onmessage = function(event) {
        document.getElementById("output").innerHTML += event.data + "<br>";
      };
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

60. ### What are the events available for server sent events?
    Below are the list of events available for server sent events
    | Event | Description |
    |---- | ---------
    | onopen  | It is used when a connection to the server is opened |
    | onmessage | This event is used when a message is received  |
    | onerror | It happens when an error occurs|

    **[⬆ Back to Top](#table-of-contents)**

61. ### What are the main rules of promise?
    A promise must follow a specific set of rules,
    1. A promise is an object that supplies a standard-compliant `.then()` method
    2. A pending promise may transition into either fulfilled or rejected state
    3. A fulfilled or rejected promise is settled and it must not transition into any other state.
    4. Once a promise is settled, the value must not change.

    **[⬆ Back to Top](#table-of-contents)**

62. ### What is callback in callback?
    You can nest one callback inside in another callback to execute the actions sequentially one by one. This is known as callbacks in callbacks.
    ```javascript
    loadScript('/script1.js', function(script) {
       console.log('first script is loaded');

      loadScript('/script2.js', function(script) {

        console.log('second script is loaded');

        loadScript('/script3.js', function(script) {

            console.log('third script is loaded');
          // after all scripts are loaded
        });

      })

    });
    ```

    **[⬆ Back to Top](#table-of-contents)**

63. ### What is promise chaining?
    The process of executing a sequence of asynchronous tasks one after another using promises is known as Promise chaining. Let's take an example of promise chaining for calculating the final result,
    ```javascript
    new Promise(function(resolve, reject) {

      setTimeout(() => resolve(1), 1000);

    }).then(function(result) {

      console.log(result); // 1
      return result * 2;

    }).then(function(result) {

      console.log(result); // 2
      return result * 3;

    }).then(function(result) {

      console.log(result); // 6
      return result * 4;

    });
    ```
    In the above handlers, the result is passed to the chain of .then() handlers with the below work flow,
    1. The initial promise resolves in 1 second,
    2. After that `.then` handler is called by logging the result(1) and then return a promise with the value of result * 2.
    3. After that the value passed to the next `.then` handler by logging the result(2) and return a promise with result * 3.
    4. Finally the value passed to the last `.then` handler by logging the result(6) and return a promise with result * 4.

    **[⬆ Back to Top](#table-of-contents)**

64. ### What is promise.all?
    Promise.all is a promise that takes an array of promises as an input (an iterable), and it gets resolved when all the promises get resolved or any one of them gets rejected. For example, the syntax of promise.all method is below,
    ```javascript
    Promise.all([Promise1, Promise2, Promise3]) .then(result) => {   console.log(result) }) .catch(error => console.log(`Error in promises ${error}`))
    ```
    **Note:** Remember that the order of the promises(output the result) is maintained as per input order.

    **[⬆ Back to Top](#table-of-contents)**

65. ### What is the purpose of race method in promise?
    Promise.race() method will return the promise instance which is firstly resolved or rejected. Let's take an example of race() method where promise2 is resolved first
    ```javascript
    var promise1 = new Promise(function(resolve, reject) {
        setTimeout(resolve, 500, 'one');
    });
    var promise2 = new Promise(function(resolve, reject) {
        setTimeout(resolve, 100, 'two');
    });

    Promise.race([promise1, promise2]).then(function(value) {
      console.log(value); // "two" // Both promises will resolve, but promise2 is faster
    });
    ```

    **[⬆ Back to Top](#table-of-contents)**

67. ### Why do you need strict mode?
    Strict mode is useful to write "secure" JavaScript by notifying "bad syntax" into real errors. For example, it eliminates accidentally creating a global variable by throwing an error and also throws an error for assignment to a non-writable property, a getter-only property, a non-existing property, a non-existing variable, or a non-existing object.

    **[⬆ Back to Top](#table-of-contents)**

71. ### What is typeof operator?
    You can use the JavaScript typeof operator to find the type of a JavaScript variable. It returns the type of a variable or an expression.
    ```javascript
    typeof "John Abraham"     // Returns "string"
    typeof (1 + 2)        // Returns "number"
    ```

    **[⬆ Back to Top](#table-of-contents)**

74. ### What is the difference between null and undefined?
    Below are the main differences between null and undefined,

    | Null | Undefined |
    |---- | -----------|
    | It is an assignment value which indicates that variable points to no object.  | It is not an assignment value where a variable has been declared but has not yet been assigned a value. |
    | Type of null is object | Type of undefined is undefined  |
    | The null value is a primitive value that represents the null, empty, or non-existent reference. | The undefined value is a primitive value used when a variable has not been assigned a value.|
    | Indicates the absence of a value for a variable | Indicates absence of variable itself |
    | Converted to zero (0) while performing primitive operations | Converted to NaN while performing primitive operations |

    **[⬆ Back to Top](#table-of-contents)**

76. ### What is the difference between window and document?
    Below are the main differences between window and document,

    | Window | Document |
    |---- | ---------
    | It is the root level element in any web page  | It is the direct child of the window object. This is also known as Document Object Model(DOM) |
    | By default window object is available implicitly in the page | You can access it via window.document or document.  |
    | It has methods like alert(), confirm() and properties like document, location | It provides methods like getElementById, getElementByTagName, createElement etc  |

    **[⬆ Back to Top](#table-of-contents)**

77. ### How do you access history in javascript?
    The window.history object contains the browsers history. You can load previous and next URLs in the history using back() and next() methods.
    ```javascript
    function goBack() {
      window.history.back()
    }
    function goForward() {
      window.history.forward()
    }
    ```
    **Note:** You can also access history without window prefix.

    **[⬆ Back to Top](#table-of-contents)**

79. ### What is isNaN?
    The isNaN() function is used to determine whether a value is an illegal number (Not-a-Number) or not. i.e, This function returns true if the value equates to NaN. Otherwise it returns false.
    ```javascript
    isNaN('Hello') //true
    isNaN('100') //false
    ```

    **[⬆ Back to Top](#table-of-contents)**

80. ### What are the differences between undeclared and undefined variables?
    Below are the major differences between undeclared and undefined variables,

    | undeclared | undefined |
    |---- | ---------
    | These variables do not exist in a program and are not declared  | These variables declared in the program but have not assigned any value |
    | If you try to read the value of an undeclared variable, then a runtime error is encountered | If you try to read the value of an undefined variable, an undefined value is returned.  |

    **[⬆ Back to Top](#table-of-contents)**

85. ### What is an event flow?
    Event flow is the order in which event is received on the web page. When you click an element that is nested in various other elements, before your click actually reaches its destination, or target element, it must trigger the click event each of its parent elements first, starting at the top with the global window object.
    There are two ways of event flow
    1. Top to Bottom(Event Capturing)
    2. Bottom to Top (Event Bubbling)

    **[⬆ Back to Top](#table-of-contents)**

86. ### What is event bubbling?
    Event bubbling is a type of event propagation where the event first triggers on the innermost target element, and then successively triggers on the ancestors (parents) of the target element in the same nesting hierarchy till it reaches the outermost DOM element.
    
    Event bubbling directs an event to its intended target, it works like this:
- A button is clicked and the event is directed to the button
- If an event handler is set for that object, the event is triggered
- If no event handler is set for that object, the event bubbles up (like a bubble in water) to the object’s parent


    **[⬆ Back to Top](#table-of-contents)**

87. ### What is event capturing?
    Event capturing is a type of event propagation where the event is first captured by the outermost element, and then successively triggers on the descendants (children) of the target element in the same nesting hierarchy till it reaches the innermost DOM element.

    **[⬆ Back to Top](#table-of-contents)**

90. ### What is the difference between document load and DOMContentLoaded events?
    The `DOMContentLoaded` event is fired when the initial HTML document has been completely loaded and parsed, without waiting for assets(stylesheets, images, and subframes) to finish loading. Whereas The load event is fired when the whole page has loaded, including all dependent resources(stylesheets, images).

    **[⬆ Back to Top](#table-of-contents)**

93. ### What are the pros and cons of promises over callbacks?
    Below are the list of pros and cons of promises over callbacks,

    **Pros:**
    1. It avoids callback hell which is unreadable
    2. Easy to write sequential asynchronous code with .then()
    3. Easy to write parallel asynchronous code with Promise.all()
    4. Solves some of the common problems of callbacks(call the callback too late, too early, many times and swallow errors/exceptions)

    **Cons:**
    1. It makes little complex code
    2. You need to load a polyfill if ES6 is not supported

    **[⬆ Back to Top](#table-of-contents)**

94. ### What is the difference between an attribute and a property?
    Attributes are defined on the HTML markup whereas properties are defined on the DOM. For example, the below HTML element has 2 attributes type and value,
    ```javascript
    <input type="text" value="Name:">
    ```
    You can retrieve the attribute value as below,
    ```javascript
    const input = document.querySelector('input');
    console.log(input.getAttribute('value')); // Good morning
    console.log(input.value); // Good morning
    ```
    And after you change the value of the text field to "Good evening", it becomes like
    ```javascript
    console.log(input.getAttribute('value')); // Good morning
    console.log(input.value); // Good evening
    ```

    **[⬆ Back to Top](#table-of-contents)**

95. ### What is same-origin policy?
    The same-origin policy is a policy that prevents JavaScript from making requests across domain boundaries. An origin is defined as a combination of URI scheme, hostname, and port number. If you enable this policy then it prevents a malicious script on one page from obtaining access to sensitive data on another web page using Document Object Model(DOM).

    **[⬆ Back to Top](#table-of-contents)**

96. ### What is the purpose of void 0?
    Void(0) is used to prevent the page from refreshing. This will be helpful to eliminate the unwanted side-effect, because it will return the undefined primitive value. It is commonly used for HTML document that uses href="JavaScript:Void(0);" within an <a> element. i.e, when you click a link, the browser loads a new page or refreshes the same page. But this behavior will be prevented using this expression.
    For example, the below link notify the message without reloading the page
    ```javascript
    <a href="JavaScript:void(0);" onclick="alert('Well done!')">Click Me!</a>
    ```

    **[⬆ Back to Top](#table-of-contents)**

97. ### Is JavaScript a compiled or interpreted language?
    JavaScript is an interpreted language, not a compiled language. An interpreter in the browser reads over the JavaScript code, interprets each line, and runs it. Nowadays  modern browsers use a technology known as Just-In-Time (JIT) compilation, which compiles JavaScript to executable bytecode just as it is about to run.

    **[⬆ Back to Top](#table-of-contents)**

100. ### What are events?
     Events are "things" that happen to HTML elements. When JavaScript is used in HTML pages, JavaScript can `react` on these events. Some of the examples of HTML events are,

     1. Web page has finished loading
     2. Input field was changed
     3. Button was clicked

     Let's describe the behavior of click event for button element,

     ```javascript
     <!doctype html>
     <html>
      <head>
        <script>
          function greeting() {
            alert('Hello! Good morning');
          }
        </script>
      </head>
      <body>
        <button type="button" onclick="greeting()">Click me</button>
      </body>
     </html>
     ```

     **[⬆ Back to Top](#table-of-contents)**

102. ### What is the use of preventDefault method?
     The preventDefault() method cancels the event if it is cancelable, meaning that the default action or behaviour that belongs to the event will not occur. For example, prevent form submission when clicking on submit button and prevent opening the page URL when clicking on hyper link are some common usecases.
     ```javascript
     document.getElementById("link").addEventListener("click", function(event){
      event.preventDefault();
     });
     ```
     **Note:** Remember that not all events are cancelable.

     **[⬆ Back to Top](#table-of-contents)**

103. ### What is the use of stopPropagation method?
     The stopPropagation method is used to stop the event from bubbling up the event chain. For example, the below nested divs with stopPropagation method prevents default event propagation when clicking on nested div(Div1)
     ```javascript
     <p>Click DIV1 Element</p>
     <div onclick="secondFunc()">DIV 2
       <div onclick="firstFunc(event)">DIV 1</div>
     </div>

     <script>
     function firstFunc(event) {
       alert("DIV 1");
       event.stopPropagation();
     }

     function secondFunc() {
       alert("DIV 2");
     }
     </script>
     ```

     **[⬆ Back to Top](#table-of-contents)**

104. ### What are the steps involved in return false usage?
     The return false statement in event handlers performs the below steps,

     1. First it stops the browser's default action or behaviour.
     2. It prevents the event from propagating the DOM
     3. Stops callback execution and returns immediately when called.

     **[⬆ Back to Top](#table-of-contents)**

105. ### What is BOM?
     The Browser Object Model (BOM) allows JavaScript to "talk to" the browser. It consists of the objects navigator, history, screen, location and document which are children of window. The Browser Object Model is not standardized and can change based on different browsers.

     ![Screenshot](images/bom.png)

     **[⬆ Back to Top](#table-of-contents)**

106. ### What is the use of setTimeout?
     The setTimeout() method is used to call a function or evaluates an expression after a specified number of milliseconds. For example, let's log a message after 2 seconds using setTimeout method,
     ```javascript
     setTimeout(function(){ console.log("Good morning"); }, 2000);
     ```

     **[⬆ Back to Top](#table-of-contents)**

107. ### What is the use of setInterval?
     The setInterval() method is used to call a function or evaluates an expression at specified intervals (in milliseconds). For example, let's log a message after 2 seconds using setInterval method,
     ```javascript
     setInterval(function(){ console.log("Good morning"); }, 2000);
     ```

     **[⬆ Back to Top](#table-of-contents)**

108. ### Why is JavaScript treated as Single threaded?
     JavaScript is a single-threaded language. Because the language specification does not allow the programmer to write code so that the interpreter can run parts of it in parallel in multiple threads or processes. Whereas languages like java, go, C++ can make multi-threaded and multi-process programs.

     **[⬆ Back to Top](#table-of-contents)**

109. ### What is an event delegation?
     Event delegation is a technique for listening to events where you delegate a parent element as the listener for all of the events that happen inside it.

     For example, if you wanted to detect field changes in inside a specific form, you can use event delegation technique,

     ```javascript
     var form = document.querySelector('#registration-form');

     // Listen for changes to fields inside the form
     form.addEventListener('input', function (event) {

     	// Log the field that was changed
     	console.log(event.target);

     }, false);
     ```

     **[⬆ Back to Top](#table-of-contents)**


113. ### What is the purpose JSON stringify?
     When sending data to a web server, the data has to be in a string format.

     **[⬆ Back to Top](#table-of-contents)**

114. ### How do you parse JSON string?
     When receiving the data from a web server, the data is always in a string format.

     **[⬆ Back to Top](#table-of-contents)**

117. ### What is the purpose of clearTimeout method?
     The clearTimeout() function is used in javascript to clear the timeout which has been set by setTimeout()function before that. i.e, The return value of setTimeout() function is stored in a variable and it’s passed into the clearTimeout() function to clear the timer.

     For example, the below setTimeout method is used to display the message after 3 seconds. This timeout can be cleared by clearTimeout() method.

     ```javascript
     <script>
     var msg;
     function greeting() {
        alert('Good morning');
     }
     function start() {
       msg =setTimeout(greeting, 3000);

     }

     function stop() {
         clearTimeout(msg);
     }
     </script>
     ```

     **[⬆ Back to Top](#table-of-contents)**

118. ### What is the purpose of clearInterval method?
     The clearInterval() function is used in javascript to clear the interval which has been set by setInterval() function. i.e, The return value returned by setInterval() function is stored in a variable and it’s passed into the clearInterval() function to clear the interval.

     For example, the below setInterval method is used to display the message for every 3 seconds. This interval can be cleared by clearInterval() method.

     ```javascript
     <script>
     var msg;
     function greeting() {
        alert('Good morning');
     }
     function start() {
       msg = setInterval(greeting, 3000);

     }

     function stop() {
         clearInterval(msg);
     }
     </script>
     ```

     **[⬆ Back to Top](#table-of-contents)**

119. ### How do you redirect new page in javascript?
     In vanilla javascript, you can redirect to a new page using `location` property of window object. The syntax would be as follows,
     ```javascript
     function redirect() {
        window.location.href = 'newPage.html';
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

123. ### What are the various url properties of location object?
     The below `Location` object properties can be used to access URL components of the page,
     1. href - The entire URL
     2. protocol - The protocol of the URL
     3. host - The hostname and port of the URL
     4. hostname - The hostname of the URL
     5. port - The port number in the URL
     6. pathname - The path name of the URL
     7. search - The query portion of the URL
     8. hash - The anchor portion of the URL

     **[⬆ Back to Top](#table-of-contents)**

132. ### How do you compare two date objects?
     You need to use use date.getTime() method to compare date values instead comparision operators (==, !=, ===, and !== operators)
     ```javascript
     var d1 = new Date();
     var d2 = new Date(d1);
     console.log(d1.getTime() === d2.getTime()); //True
     console.log(d1 === d2); // False
     ```

     **[⬆ Back to Top](#table-of-contents)**

137. ### How do you assign default values to variables?
     You can use the logical or operator `||` in an assignment expression to provide a default value. The syntax looks like as below,
     ```javascript
     var a = b || c;
     ```
     As per the above expression, variable 'a 'will get the value of 'c' only if 'b' is falsy (if is null, false, undefined, 0, empty string, or NaN), otherwise 'a' will get the value of 'b'.

     **[⬆ Back to Top](#table-of-contents)**

142. ### What is a polyfill?
     A polyfill is a piece of JS code used to provide modern functionality on older browsers that do not natively support it. For example, Silverlight plugin polyfill can be used to mimic the functionality of an HTML Canvas element on Microsoft Internet Explorer 7.

     **[⬆ Back to Top](#table-of-contents)**

145. ### What are the benefits of keeping declarations at the top?
     It is recommended to keep all declarations at the top of each script or function. The benefits of doing this are,
     1. Gives cleaner code
     2. It provides a single place to look for local variables
     3. Easy to avoid unwanted global variables
     4. It reduces the possibility of unwanted re-declarations

     **[⬆ Back to Top](#table-of-contents)**

149. ### How do you generate random integers?
     You can use Math.random() with Math.floor() to return random integers. For example, if you want generate random integers between 1 to 10, the multiplication factor should be 10,
     ```javascript
     Math.floor(Math.random() * 10) + 1;     // returns a random integer from 1 to 10
     Math.floor(Math.random() * 100) + 1;     // returns a random integer from 1 to 100
     ```
     **Note:** Math.random() returns a random number between 0 (inclusive),  and 1 (exclusive)

     **[⬆ Back to Top](#table-of-contents)**

151. ### What is tree shaking?
     Tree shaking is a form of dead code elimination. It means that unused modules will not be included in the bundle during the build process and for that it relies on the static structure of ES2015 module syntax,( i.e. import and export). Initially this has been popularized by the ES2015 module bundler `rollup`.

     **[⬆ Back to Top](#table-of-contents)**

152. ### What is the need of tree shaking?
     Tree Shaking can significantly reduce the code size in any application. i.e, The less code we send over the wire the more performant the application will be. For example, if we just want to create a “Hello World” Application using SPA frameworks then it will take around  few MBs, but by tree shaking it can bring down the size to just few hundred KBs. Tree shaking is been implemented in Rollup and Webpack bundlers.

     **[⬆ Back to Top](#table-of-contents)**

156. ### What are modifiers in regular expression?
     Modifiers can be used to perform case-insensitive and global searches. Let's list down some of the modifiers,

     | Modifier | Description |
     |---- | ---------
     | i  | Perform case-insensitive matching |
     | g | 	Perform a global match rather than stops at first match  |
     | m | Perform multiline matching|

    Let's take an example of global modifier,
    ```javascript
      var text = "Learn JS one by one";
      var pattern = /one/g;
      var result = text.match(pattern); // one,one
    ```

   **[⬆ Back to Top](#table-of-contents)**

157. ### What are regular expression patterns?
     Regular Expressions provided group of patterns in order to match characters. Basically they are categorized into 3 types,
     1. **Brackets:** These are used to find a range of characters.
        For example, below are some use cases,
        1. [abc]: Used to find any of the characters between the brackets(a,b,c)
        2. [0-9]: Used to find any of the digits between the brackets
        3. (a|b): Used to find any of the alternatives separated with |
     2. **Metacharacters:** These are characters with a special meaning
        For example, below are some use cases,
        1. \d: Used to find a digit
        2. \s: Used to find a whitespace character
        3. \b: Used to find a match at the beginning or ending of a word
     3. **Quantifiers:** These are useful to define quantities
        For example, below are some use cases,
        1. n+: Used to find matches for any string that contains at least one n
        2. n*: Used to find matches for any string that contains zero or more occurrences of n
        3. n?: Used to find	matches for any string that contains zero or one occurrences of n

     **[⬆ Back to Top](#table-of-contents)**

158. ### What is a RegExp object?
     RegExp object is a regular expression object with predefined properties and methods. Let's see the simple usage of RegExp object,
     ```javascript
     var regexp = new RegExp('\\w+');
     console.log(regexp);
     // expected output: /\w+/
     ```

     **[⬆ Back to Top](#table-of-contents)**

159. ### How do you search a string for a pattern?
     You can use test() method of regular expression in order to search a string for a pattern, and returns true or false depending on the result.
     ```javascript
     var pattern = /you/;
     console.log(pattern.test("How are you?")); //true
     ```

     **[⬆ Back to Top](#table-of-contents)**

161. ### How do you change style of a HTML element?
     You can change inline style or classname of a HTML element using javascript
     1. ** Using style property:** You can modify inline style using style property
     ```javascript
     document.getElementById("title").style.fontSize = "30px";
     ```
     2. ** Using ClassName property:** It is easy to modify element class using className property
     ```javascript
      document.getElementById("title").style.className = "custom-title";
      ```

     **[⬆ Back to Top](#table-of-contents)**

167. ### How do you detect a mobile browser without regexp?
     You can detect mobile browser by simply running through a list of devices and checking if the useragent matches anything. This is an alternative solution for RegExp usage,
     ```javascript
     function detectmob() {
      if( navigator.userAgent.match(/Android/i)
      || navigator.userAgent.match(/webOS/i)
      || navigator.userAgent.match(/iPhone/i)
      || navigator.userAgent.match(/iPad/i)
      || navigator.userAgent.match(/iPod/i)
      || navigator.userAgent.match(/BlackBerry/i)
      || navigator.userAgent.match(/Windows Phone/i)
      ){
         return true;
       }
      else {
         return false;
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

168. ### How do you get the image width and height using JS?
     You can programmatically get the image and check the dimensions(width and height) using Javascript.
     ```javascript
     var img = new Image();
     img.onload = function() {
       console.log(this.width + 'x' + this.height);
     }
     img.src = 'http://www.google.com/intl/en_ALL/images/logo.gif';
     ```

     **[⬆ Back to Top](#table-of-contents)**

169. ### How do you make synchronous HTTP request?
     Browsers provide an XMLHttpRequest object which can be used to make synchronous HTTP requests from JavaScript
     ```javascript
     function httpGet(theUrl)
     {
         var xmlHttpReq = new XMLHttpRequest();
         xmlHttpReq.open( "GET", theUrl, false ); // false for synchronous request
         xmlHttpReq.send( null );
         return xmlHttpReq.responseText;
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

170. ### How do you make asynchronous HTTP request?
     Browsers provide an XMLHttpRequest object which can be used to make asynchronous HTTP requests from JavaScript by passing 3rd parameter as true.
     ```javascript
     function httpGetAsync(theUrl, callback)
     {
         var xmlHttpReq = new XMLHttpRequest();
         xmlHttpReq.onreadystatechange = function() {
             if (xmlHttpReq.readyState == 4 && xmlHttpReq.status == 200)
                 callback(xmlHttpReq.responseText);
         }
         xmlHttp.open("GET", theUrl, true); // true for asynchronous
         xmlHttp.send(null);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

172. ### What are the properties used to get size of window?
     You can use innerWidth, innerHeight, clientWidth, clientHeight properties of windows, document element and document body objects to find the size of a window. Let's use them combination of these properties to calculate the size of a window or document,
     ```javascript
     var width = window.innerWidth
     || document.documentElement.clientWidth
     || document.body.clientWidth;

     var height = window.innerHeight
     || document.documentElement.clientHeight
     || document.body.clientHeight;
     ```

     **[⬆ Back to Top](#table-of-contents)**

175. ### What are the ways to execute javascript after page load?
     You can execute javascript after page load in many different ways,
     1. **window.onload:**
     ```javascript
     window.onload = function ...
     ```
     2. **document.onload:**
     ```javascript
     document.onload = function ...
     ```
     3. **body onload:**
     ```javascript
     <body onload="script();">
     ```

     **[⬆ Back to Top](#table-of-contents)**

176. ### What is the difference between proto and prototype?
     The `__proto__` object is the actual object that is used in the lookup chain to resolve methods, etc. Whereas `prototype` is the object that is used to build `__proto__` when you create an object with new
     ```javascript
     ( new Employee ).__proto__ === Employee.prototype;
     ( new Employee ).prototype === undefined;
     ```

     **[⬆ Back to Top](#table-of-contents)**

178. ### What is a freeze method?
     The **freeze()** method is used to freeze an object. Freezing an object does'nt allow adding new properties to an object,prevents from removing and prevents changing the enumerability, configurability, or writability of existing properties. i.e, It returns the passed object and does not create a frozen copy.
     ```javascript
     const obj = {
       prop: 100
     };

     Object.freeze(obj);
     obj.prop = 200; // Throws an error in strict mode

     console.log(obj.prop); //100
     ```
     **Note:** It causes a TypeError if the argument passed is not an object.

     **[⬆ Back to Top](#table-of-contents)**

179. ### What is the purpose of freeze method?
     Below are the main benefits of using freeze method,

     1. It is used for freezing objects and arrays.
     2. It is used to make an object immutable.

     **[⬆ Back to Top](#table-of-contents)**

180. ### Why do I need to use freeze method?
     In Object-oriented paradigm, an existing API contains certain elements that are not intended to be extended, modified, or re-used outside of their current context. Hence it works as `final` keyword which is used in various languages.

     **[⬆ Back to Top](#table-of-contents)**

181. ### How do you detect a browser language preference?
     You can use navigator object to detect a browser language preference as below,
     ```javascript
     var language = navigator.languages && navigator.languages[0] || // Chrome / Firefox
                    navigator.language ||   // All browsers
                    navigator.userLanguage; // IE <= 10

     console.log(language);
     ```

     **[⬆ Back to Top](#table-of-contents)**

183. ### How do you detect javascript disabled in the page?
     You can use `<noscript>` tag to detect javascript disabled or not. The code block inside `<noscript>` get executed when JavaScript is disabled, and are typically used to display alternative content when the page generated in JavaScript.
     ```javascript
     <script type="javascript">
         // JS related code goes here
     </script>
     <noscript>
         <a href="next_page.html?noJS=true">JavaScript is disabled in the apge. Please click Next Page</a>
     </noscript>
     ```

     **[⬆ Back to Top](#table-of-contents)**

187. ### What are the bitwise operators available in javascript?
     Below are the list of bit-wise logical operators used in JavaScript
     1. Bit-wise AND ( & )
     2. Bit-Wise OR ( | )
     3. Bit-Wise XOR ( ^ )
     4. Bit-Wise NOT ( ~ )
     5. Left Shift ( << )
     6. Sign Propagating Right Shift ( >> )
     7. Zero fill Right Shift ( >>> )

     **[⬆ Back to Top](#table-of-contents)**

188. ### What is a spread operator?
     Spread operator allows iterables( arrays / objects / strings ) to be expanded into single arguments/elements. Let's take an example to see this behavior,
     ```javascript
     function calculateSum(x, y, z) {
       return x + y + z;
     }

     const numbers = [1, 2, 3];

     console.log(calculateSum(...numbers)); // 6
     ```

     **[⬆ Back to Top](#table-of-contents)**

195. ### What is the purpose of seal method?
     The **Object.seal()** method is used seal an object, by preventing new properties from being added to it and marking all existing properties as non-configurable. But values of present properties can still be changed as long as they are writable. Let's see the below example to understand more about seal() method
     ```javascript
      const object = {
         property: 'Welcome JS world'
      };
      Object.seal(object);
      object.property = 'Welcome to object world';
      console.log(Object.isSealed(object)); // true
      delete object.property; // You cannot delete when sealed
      console.log(object.property); //Welcome to object world
     ```

     **[⬆ Back to Top](#table-of-contents)**

197. ### What are the differences between freeze and seal methods?
     If an object is frozen using the Object.freeze() method then its properties become immutable and no changes can be made in them whereas if an object is sealed using the Object.seal() method then the changes can be made in the existing properties of the object.

     **[⬆ Back to Top](#table-of-contents)***

214. ### What is an anonymous function?
     An anonymous function is a function without a name! Anonymous functions are commonly assigned to a variable name or used as a callback function. The syntax would be as below,
     ```javascript
     function (optionalParameters) {
       //do something
     }

     const myFunction = function(){ //Anonymous function assigned to a variable
       //do something
     };

     [1, 2, 3].map(function(element){ //Anonymous function used as a callback function
       //do something
     });
     ```
     Let's see the above anonymous function in an example,
     ```javascript
     var x = function (a, b) {return a * b};
     var z = x(5, 10);
     console.log(z); // 50
     ```
     - They could have names which is necessary for a recursive function

     **[⬆ Back to Top](#table-of-contents)**

216. ### What are javascript accessors?
     ECMAScript 5 introduced javascript object accessors or computed properties through getters and setters. Getters uses `get` keyword whereas Setters uses `set` keyword.
     ```javascript
     var user = {
       firstName: "John",
       lastName : "Abraham",
       language : "en",
       get lang() {
         return this.language;
       }
       set lang(lang) {
       this.language = lang;
       }
     };
     console.log(user.lang); // getter access lang as en
     user.lang = 'fr';
     console.log(user.lang); // setter used to set lang as fr
     ```

     **[⬆ Back to Top](#table-of-contents)**

219. ### What are the advantages of Getters and Setters?
     Below are the list of benefits of Getters and Setters,
     1. They provide simpler syntax
     2. They are used for defining computed properties, or accessors in JS.
     3. Useful to provide equivalence relation between properties and methods
     4. They can provide better data quality
     5. Useful for doing things behind the scenes with the encapsulated logic.

     **[⬆ Back to Top](#table-of-contents)**

225. ### What are the function parameter rules?
     JavaScript functions follow below rules for parameters,
     1. The function definitions do not specify data types for parameters.
     2. Do not perform type checking on the passed arguments.
     3. Do not check the number of arguments received.
     i.e, The below function follows the above rules,
     ```javascript
     function functionName(parameter1, parameter2, parameter3) {
       console.log(parameter1); // 1
     }
     functionName(1);
     ```

     **[⬆ Back to Top](#table-of-contents)**

226. ### What is an error object?
     An error object is a built in error object that provides error information when an error occurs. It has two properties: name and message. For example, the below function logs error details,
     ```javascript
     try {
       greeting("Welcome");
     }
     catch(err) {
       console.log(err.name + "<br>" + err.message);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

229. ### What are the various statements in error handling?
     Below are the list of statements used in an error handling,
     1. **try:** This statement is used to test a block of code for errors
     2. **catch:** This statement is used to handle the error
     3. **throw:** This statement is used to create custom errors.
     4. **finally:** This statement is used to execute code after try and catch regardless of the result.

     **[⬆ Back to Top](#table-of-contents)**

231. ### What is nodejs?
     Node.js is a server-side platform built on Chrome's JavaScript runtime for easily building fast and scalable network applications. It is an event-based, non-blocking, asynchronous I/O runtime that uses Google's V8 JavaScript engine and libuv library.

     **[⬆ Back to Top](#table-of-contents)**

234. ### What is an Iterator?
     An iterator is an object which defines a sequence and a return value upon its termination. It implements the Iterator protocol with a `next()` method which returns an object with two properties: `value` (the next value in the sequence) and `done` (which is true if the last value in the sequence has been consumed).

     **[⬆ Back to Top](#table-of-contents)**

234. ### How does synchronous iteration works?
     Synchronous iteration was introduced in ES6 and it works with below set of components,

     **Iterable:** It is an object which can be iterated over via a method whose key is Symbol.iterator.
     **Iterator:** It is an object returned by invoking `[Symbol.iterator]()` on an iterable. This iterator object wraps each iterated element in an object and returns it via `next()` method one by one.
     **IteratorResult:** It is an object returned by `next()` method. The object contains two properties; the `value` property contains an iterated element and the `done` property  determines whether the element is last element or not.

     Let's demonstrate synchronous iteration with an array as below,

     ```js
     const iterable = ['one', 'two', 'three'];
     const iterator = iterable[Symbol.iterator]();
     console.log(iterator.next());  // { value: 'one', done: false }
     console.log(iterator.next());  // { value: 'two', done: false }
     console.log(iterator.next());  // { value: 'three', done: false }
     console.log(iterator.next());  // { value: 'undefined, done: true }
     ```
     **[⬆ Back to Top](#table-of-contents)**

235. ### What is an event loop?
     The Event Loop is a queue of callback functions. When an async function executes, the callback function is pushed into the queue. The JavaScript engine doesn't start processing the event loop until async function has finished executing the code.
     **Note:** It allows Node.js to perform non-blocking I/O operations even though JavaScript is single-threaded.

     **[⬆ Back to Top](#table-of-contents)**

236. ### What is call stack?
     Call Stack is a data structure for javascript interpreter to keeps track of function calls in the program. It has two major actions,
     1. Whenever you call a function for its execution, you are pushing it to the stack.
     2. Whenever the execution is completed, the function is popped out of the stack.

     ![Screenshot](images/call-stack.png)

     **[⬆ Back to Top](#table-of-contents)**

237. ### What is an event queue?

     **[⬆ Back to Top](#table-of-contents)**

238. ### What is a decorator?
     A decorator is an expression that evaluates to a function and that takes the target, name, and decorator descriptor as arguments. Also, it optionally returns a decorator descriptor to install on the target object. Let's define admin decorator for user class at design time,
     ```javascript
     function admin(isAdmin) {
        return function(target) {
            target.isAdmin = isAdmin;
        }
     }

     @admin(true)
     class User() {
     }
     console.log(User.isAdmin); //true

      @admin(false)
      class User() {
      }
      console.log(User.isAdmin); //false
     ```

     **[⬆ Back to Top](#table-of-contents)**

250. ### What is typescript?
    TypeScript is a typed superset of JavaScript created by Microsoft that adds optional types, classes, async/await, and many other features, and compiles to plain JavaScript. Angular is built entirely in TypeScript and used as a primary language.
    You can install it globally as
    ```
    npm install -g typescript
    ```
    Let's see a simple example of TypeScript usage,
    ```typescript
    function greeting(person: string) {
        return "Hello, " + person;
    }

    let user = "Sudheer";

    document.body.innerHTML = greeting(user);
    ```
    The greeting method allows only string type as argument.

   **[⬆ Back to Top](#table-of-contents)**

251. ### What are the differences between javascript and typescript?
     Below are the list of differences between javascript and typescript,

     | feature | typescript | javascript |
     |---- | --------- | ----
     | Language paradigm  | Object oriented programming language  | Scripting language |
     | Typing support | Supports static typing  | It has dynamic typing |
     | Modules | Supported | Not supported |
     | Interface | It has interfaces concept | Doesn't support interfaces |
     | Optional parameters | Functions support optional parameters | No support of optional parameters for functions |

     **[⬆ Back to Top](#table-of-contents)**

252. ### What are the advantages of typescript over javascript?
     Below are some of the advantages of typescript over javascript,
     1. TypeScript is able to find compile time errors at the development time only and it make sures less runtime errors. Whereas javascript is interpreted language.
     2. TypeScript is is strongly-typed or supports static typing which allows for checking type correctness at compile time. This is not available in javascript.
     3. TypeScript compiler can compile the .ts files into ES3,ES4 and ES5 unlike ES6 features of javascript which may not be supported in some browsers.

     **[⬆ Back to Top](#table-of-contents)**

256. ### How do you call the constructor of a parent class?
     You can use `super` keyword to call the constructor of a parent class. Remember that `super()` must be called before using 'this' reference. Otherwise it will cause a reference error. Let's see the usage of it,
     ```javascript
     class Square extends Rectangle {
       constructor(length) {
         super(length, length);
         this.name = 'Square';
       }

       get area() {
         return this.width * this.height;
       }

       set area(value) {
         this.area = value;
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

265. ### What Is Obfuscation in javascript?
     Obfuscation is the deliberate act of creating obfuscated javascript code(i.e, source or machine code) that is difficult for humans to understand. It is something similar to encryption, but a machine can understand the code and execute it.
     Let's see the below function before Obfuscation,
     ```javascript
     function greeeting() {
        console.log('Hello, welcome to JS world');
     }
     ```
     And after the code Obfuscation, it would be appeared as below,
     ```javascript
     eval(function(p,a,c,k,e,d){e=function(c){return c};if(!''.replace(/^/,String)){while(c--){d[c]=k[c]||c}k=[function(e){return d[e]}];e=function(){return'\\w+'};c=1};while(c--){if(k[c]){p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c])}}return p}('2 1(){0.3(\'4, 7 6 5 8\')}',9,9,'console|greeeting|function|log|Hello|JS|to|welcome|world'.split('|'),0,{}))
     ```

     **[⬆ Back to Top](#table-of-contents)**

266. ### Why do you need Obfuscation?
     Below are the few reasons for Obfuscation,
     1. The Code size will be reduced. So data transfers between server and client will be fast.
     2. It hides the business logic from outside world and protects the code from others
     3. Reverse engineering is highly difficult
     4. The download time will be reduced

     **[⬆ Back to Top](#table-of-contents)**

267. ### What is Minification?
     Minification is the process of removing all unnecessary characters(empty spaces are removed) and variables will be renamed without changing it's functionality. It is also a type of obfuscation .

     **[⬆ Back to Top](#table-of-contents)**

268. ### What are the advantages of minification?
     Normally it is recommend to use minification for heavy traffic and intensive requirements of resources. It reduces file sizes with below benefits,
     1. Decreases loading times of a web page
     2. Saves bandwidth usages

     **[⬆ Back to Top](#table-of-contents)**

269. ### What are the differences between Obfuscation and Encryption?
     Below are the main differences between Obfuscation and Encryption,

     | Feature | Obfuscation | Encryption |
     |---- | --------- | ----
     | Definition  | Changing the form of any data in any other form  | Changing the form of information to an unreadable format by using a key |
     | A key to decode | It can be decoded without any key  | It is required |
     | Target data format | It will be converted to a complex form  | Converted into an unreadable format  |

     **[⬆ Back to Top](#table-of-contents)**

270. ### What are the common tools used for minification?
     There are many online/offline tools to minify the javascript files,
     1. Google's Closure Compiler
     2. UglifyJS2
     3. jsmin
     4. javascript-minifier.com/
     5. prettydiff.com

     **[⬆ Back to Top](#table-of-contents)**

271. ### How do you perform form validation using javascript?
     JavaScript can be used to perform HTML form validation. For example, if form field is empty, the function needs to notify, and return false, to prevent the form being submitted.
     Lets' perform user login in an html form,
     ```html
     <form name="myForm" onsubmit="return validateForm()" method="post">
     User name: <input type="text" name="uname">
     <input type="submit" value="Submit">
     </form>
     ```
     And the validation on user login is below,
     ```javascript
     function validateForm() {
       var x = document.forms["myForm"]["uname"].value;
       if (x == "") {
         alert("The username shouldn't be empty");
         return false;
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

272. ### How do you perform form validation without javascript?
     You can perform HTML form validation automatically without using javascript. The validation enabled by applying `required` attribute to prevent form submission when the input is empty.
     ```html
     <form method="post">
       <input type="text" name="uname" required>
       <input type="submit" value="Submit">
     </form>
     ```
     **Note:** Automatic form validation does not work in Internet Explorer 9 or earlier.

     **[⬆ Back to Top](#table-of-contents)**

273. ### What are the DOM methods available for constraint validation?
     The below DOM methods are available for constraint validation on an invalid input,
     1. checkValidity(): It returns true if an input element contains valid data.
     2. setCustomValidity(): It is used to set the validationMessage property of an input element.
     Let's take an user login form with DOM validations
     ```javascript
     function myFunction() {
       var userName = document.getElementById("uname");
       if (!userName.checkValidity()) {
         document.getElementById("message").innerHTML = userName.validationMessage;
       } else {
         document.getElementById("message").innerHTML = "Entered a valid username";
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

277. ### Is enums feature available in javascript?
     No, javascript does not natively support enums. But there are different kind of solutions to simulate them even though they may not provide exact equivalent. For example, you can use freeze or seal on object,
     ```javascript
     var DaysEnum = Object.freeze({"monday":1, "tuesday":2, "wednesday":3, ...})
     ```

     **[⬆ Back to Top](#table-of-contents)**

278. ### What is an enum?
     An enum is a type restricting variables to one value from a predefined set of constants. JavaScript has no enums but typescript provides built-in enum support.
     ```javascript
     enum Color {
     	RED, GREEN, BLUE
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

282. ### How do you extend classes?
     The `extends` keyword is used in class declarations/expressions to create a class which is a child of another class. It can be used to subclass custom classes as well as built-in objects. The syntax would be as below,
     ```javascript
     class ChildClass extends ParentClass { ... }
     ```
     Let's take an example of Square subclass from Polygon parent class,
     ```javascript
      class Square extends Rectangle {
        constructor(length) {
          super(length, length);
          this.name = 'Square';
        }

        get area() {
          return this.width * this.height;
        }

        set area(value) {
          this.area = value;
        }
      }
     ```

     **[⬆ Back to Top](#table-of-contents)**

283. ### How do I modify the url without reloading the page?
     The `window.localtion.url` property will be helpful to modify the url but it reloads the page. HTML5 introduced the `history.pushState()` and `history.replaceState()` methods, which allow you to add and modify history entries, respectively. For example, you can use pushState as below,
     ```javascript
     window.history.pushState('page2', 'Title', '/page2.html');
     ```

     **[⬆ Back to Top](#table-of-contents)**

286. ### How to get the value from get parameters?
     The `new URL()` object accepts url string and `searchParams` property of this object can be used to access the get parameters. Remember that you may need to use polyfill or `window.location` to access the URL in older browsers(including IE).
     ```javascript
     let urlString = "http://www.some-domain.com/about.html?x=1&y=2&z=3"; //window.location.href
     let url = new URL(urlString);
     let parameterZ = url.searchParams.get("z");
     console.log(parameterZ); // 3
     ```

     **[⬆ Back to Top](#table-of-contents)**

288. ### What is the difference between java and javascript?
     Both are totally unrelated programming languages and no relation between them. Java is statically typed, compiled, runs on its own VM. Whereas Javascript is dynamically typed, interpreted, and runs in a browser and nodejs environments. Let's see the major differences in a tabular format,
     | Feature | Java | JavaScript |
     |---- | ---------
     | Typed  | It's a strongly typed language | It's a dynamic typed language |
     | Paradigm | Object oriented programming  | Prototype based programming |
     | Scoping | Block scoped | Function-scoped |
     | Concurrency | Thread based | event based |
     | Memory | Uses more memory | Uses less memory. Hence it will be used for web pages |

     **[⬆ Back to Top](#table-of-contents)**

294. ### What are the different methods to find HTML elements in DOM?
     If you want to access any element in an HTML page, you need to start with accessing the document object. Later you can use any of the below methods to find the HTML element,
     1. document.getElementById(id): It finds an element by Id
     2. document.getElementsByTagName(name): It finds an element by tag name
     3. document.getElementsByClassName(name): It finds an element by class name

     **[⬆ Back to Top](#table-of-contents)**

295. ### What is jQuery?
     jQuery is a popular cross-browser JavaScript library that provides Document Object Model (DOM) traversal, event handling, animations and AJAX interactions by minimizing the discrepancies across browsers. It is widely famous with its philosophy of “Write less, do more”. For example, you can display welcome message on the page load using jQuery as below,
     ```javascript
     $(document).ready(function(){ // It selects the document and apply the function on page load
         alert('Welcome to jQuery world');
     });
     ```
     **Note:** You can download it from jquery official site or install it from CDNs, like google.

     **[⬆ Back to Top](#table-of-contents)**

296. ### What is V8 JavaScript engine?
     V8 is an open source high-performance JavaScript engine used by the Google Chrome browser, written in C++. It is also being used in the node.js project. It implements ECMAScript and WebAssembly, and runs on Windows 7 or later, macOS 10.12+, and Linux systems that use x64, IA-32, ARM, or MIPS processors.
     **Note:** It can run standalone, or can be embedded into any C++ application.

     **[⬆ Back to Top](#table-of-contents)**

297. ### Why do we call javascript as dynamic language?
     JavaScript is a loosely typed or a dynamic language because variables in JavaScript are not directly associated with any particular value type, and any variable can be assigned/re-assigned with values of all types.
     ```javascript
     let age = 50;    // age is a number now
     age  = 'old'; // age is a string now
     age  = true;  // age is a boolean
     ```

     **[⬆ Back to Top](#table-of-contents)**

300. ### How do you create an infinite loop?
     You can create infinite loop using for and while loops without using any expressions. The for loop construct or syntax is better approach in terms of ESLint and code optimizer tools,
     ```javascript
     for (;;) {}
     while(true) {
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

301. ### Why do you need to avoid with statement?
     JavaScript's with statement was intended to provide a shorthand for writing recurring accesses to objects. So it can help reduce file size by reducing the need to repeat a lengthy object reference without performance penalty. Let's take an example where it is used to avoid redundancy when accessing an object several times.
     ```javascript
     a.b.c.greeting   = 'welcome';
     a.b.c.age = 32;
     ```
     Using `with` it turns this into:
     ```javascript
     with(a.b.c) {
             greeting   = "welcome";
             age = 32;
     }
     ```
     But this `with` statement creates performance problems since one cannot predict whether argument will refer to a real variable or to a property inside the with argument.

     **[⬆ Back to Top](#table-of-contents)**

302. ### What is the output of below for loops?
     ```javascript
     for (var i = 0; i < 4; i++) { // global scope
       setTimeout(() => console.log(i));
     }

     for (let i = 0; i < 4; i++) { // block scope
       setTimeout(() => console.log(i));
     }
     ```
     The output of the above for loops is 4 4 4 4 and 0 1 2 3
     **Explanation:** Due to event queue/loop of javascript, the `setTimeout` callback function is called after the loop has been executed. Since the variable i is declared with `var` keyword it became a global variable and the value was equal to 4 using iteration when the time setTimeout function is invoked. Hence, the output of the first loop is `4 4 4 4`. Whereas in the second loop, the variable i is declared as `let` keyword it became a block scoped variable and it holds a new value(0, 1 ,2 3) for each iteration. Hence, the output of the first loop is `0 1 2 3`.

     **[⬆ Back to Top](#table-of-contents)**

303. ### List down some of the features of ES6?
     Below are the list of some new features of ES6,
     1. Support for constants or immutable variables
     2. Block-scope support for variables, constants and functions
     3. Arrow functions
     4. Default parameters
     5. Rest and Spread Parameters
     6. Template Literals
     7. Multi-line Strings
     8. Destructuring Assignment
     9. Enhanced Object Literals
     10. Promises
     11. Classes
     12. Modules

     **[⬆ Back to Top](#table-of-contents)**

304. ### What is ES6?
     ES6 is the sixth edition of the javascript language and it was released on June 2015. It was initially known as ECMAScript 6 (ES6) and later renamed to ECMAScript 2015. Almost all the modern browsers support ES6 but for the old browsers there are many transpilers, like Babel.js etc.

     **[⬆ Back to Top](#table-of-contents)**

305. ### Can I redeclare let and const variables?
     No, you cannot redeclare let and const variables. If you do, it throws below error
     ```bash
     Uncaught SyntaxError: Identifier 'someVariable' has already been declared
     ```
     **Explanation:** The variable declaration with `var` keyword refers to a function scope and the variable is treated as if it were declared at the top of the enclosing scope due to hoisting feature. So all the multiple declarations contributing to the same hoisted variable without any error. Let's take an example of re-declaring variables in the same scope for both var and let/const variables.
     ```javascript
     var name = 'John';
     function myFunc() {
         var name = 'Nick';
         var name = 'Abraham'; // Re-assigned in the same function block
         alert(name); // Abraham
     }
     myFunc();
     alert(name); // John
     ```
     The block-scoped multi-declaration throws syntax error,
     ```javascript
     let name = 'John';
     function myFunc() {
         let name = 'Nick';
         let name = 'Abraham'; // Uncaught SyntaxError: Identifier 'name' has already been declared
         alert(name);
     }

     myFunc();
     alert(name);
     ```

     **[⬆ Back to Top](#table-of-contents)**

306. ### Is const variable makes the value immutable?
     No, the const variable doesn't make the value immutable. But it disallows subsequent assignments(i.e, You can declare with assignment but can't assign another value later)
     ```javascript
     const userList = [];
     userList.push('John'); // Can mutate even though it can't re-assign
     console.log(userList); // ['John']
     ```

     **[⬆ Back to Top](#table-of-contents)**

307. ### What are default parameters?
     In E5, we need to depends on logical OR operator to handle default values of function parameters. Whereas in ES6, Default function parameters feature allows parameters to be initialized with default values if no value or undefined is passed. Let's compare the behavior with an examples,
     ```javascript
     //ES5
     var calculateArea = function(height, width) {
        height =  height || 50;
        width = width || 60;

        return width * height;
     }
     console.log(calculateArea()); //300
     ```
     The default parameters makes the initialization more simpler,
     ```javascript
     //ES6
     var calculateArea = function(height = 50, width = 60) {
        return width * height;
     }

     console.log(calculateArea()); //300
     ```

     **[⬆ Back to Top](#table-of-contents)**

308. ### What are template literals?
     Template literals or template strings are string literals allowing embedded expressions. These are enclosed by the back-tick (` `) character instead of double or single quotes.
     In E6, this feature enables using dynamic expressions as below,
     ```javascript
     var greeting = `Welcome to JS World, Mr. ${firstName} ${lastName}.`
     ```
     In ES5, you need break string like below,
     ```javascript
     var greeting = 'Welcome to JS World, Mr. ' + firstName + ' ' + lastName.`
     ```
     **Note:** You can use multi-line strings and string interpolation features with template literals.

     **[⬆ Back to Top](#table-of-contents)**

309. ### How do you write multi-line strings in template literals?
     In ES5, you would have to use newline escape character('\n') and concatenation symbol(+) in order to get multi-line strings.
     ```javascript
     console.log('This is string sentence 1\n' +
     'This is string sentence 2');
     ```
     Whereas in ES6, You don't need to mention any newline sequence character,
     ```javascript
     console.log(`This is string sentence
     'This is string sentence 2`);
     ```

     **[⬆ Back to Top](#table-of-contents)**

310. ### What are nesting templates?
     The nesting templates is a feature supported with in template literals syntax to allow inner backticks inside a placeholder ${ } within the template. For example, the below nesting template is used to display the icons based on user permissions whereas outer template checks for platform type,
     ```javascript
     const iconStyles = `icon ${ isMobilePlatform() ? '' :
      `icon-${user.isAuthorized ? 'submit' : 'disabled'}` }`;
     ```
     You can write the above usecase without nesting template feature as well. However, nesting template feature is more compact and readable.
     ```javascript
     //Without nesting templates
      const iconStyles = `icon ${ isMobilePlatform() ? '' :
       (user.isAuthorized ? 'icon-submit' : 'icon-disabled'}`;
     ```

     **[⬆ Back to Top](#table-of-contents)**

311. ### What are tagged templates?
     Tagged templates are the advanced form of templates in which tags allow you to parse template literals with a function. The tag function accepts first parameter as array of strings and remaining parameters as expressions. This function can also return manipulated string based on parameters. Let's see the usage of this tagged template behavior of an IT professional skill set in an organization,
     ```javascript
     var user1 = 'John';
     var skill1 = 'JavaScript';
     var experience1 = 15;

     var user2 = 'Kane';
     var skill2 = 'JavaScript';
     var experience2 = 5;

     function myInfoTag(strings, userExp, experienceExp, skillExp) {
       var str0 = strings[0]; // "Mr/Ms. "
       var str1 = strings[1]; // " is a/an "
       var str2 = strings[2]; // "in"

       var expertiseStr;
       if (experienceExp > 10){
         expertiseStr = 'expert developer';
       } else if(skillExp > 5 && skillExp <= 10) {
         expertiseStr = 'senior developer';
       } else {
         expertiseStr = 'junior developer';
       }

       return `${str0}${userExp}${str1}${experienceExp}{str3}`;
     }

     var output1 = myInfoTag`Mr/Ms. ${ user1 } is a/an ${ experience1 } in ${skill1}`;
     var output2 = myInfoTag`Mr/Ms. ${ user2 } is a/an ${ experience2 } in ${skill2}`;

     console.log(output1);// Mr/Ms. John is a/an expert developer in JavaScript
     console.log(output2);// Mr/Ms. Kane is a/an junior developer in JavaScript
     ```

     **[⬆ Back to Top](#table-of-contents)**

312. ### What are raw strings?
     ES6 provides raw strings feature using `String.raw()` method which is used to get the raw string form of template strings. This feature allows you to access the raw strings as they were entered, without processing escape sequences. For example, the usage would be as below,
     ```javascript
     var calculationString = String.raw `The sum of numbers is \n${1+2+3+4}!`;
     console.log(calculationString); // The sum of numbers is 10
     ```
     If you don't use raw strings, the newline character sequence will be processed by displaying the output in multiple lines
     ```
      var calculationString = `The sum of numbers is \n${1+2+3+4}!`;
      console.log(calculationString);
      // The sum of numbers is
      // 10
     ```
     Also, the raw property is available on the first argument to the tag function
     ```javascript
     function tag(strings) {
       console.log(strings.raw[0]);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

313. ### What is destructuring assignment?
     The destructuring assignment is a JavaScript expression that makes it possible to unpack values from arrays or properties from objects into distinct variables.
     Let's get the month values from an array using destructuring assignment
     ```javascript
     var [one, two, three] = ['JAN', 'FEB', 'MARCH'];

     console.log(one); // "JAN"
     console.log(two); // "FEB"
     console.log(three); // "MARCH"
     ```
     and you can get user properties of an object using destructuring assignment,
     ```javascript
     var {name, age} = {name: 'John', age: 32};

     console.log(name); // John
     console.log(age); // 32
     ```

     **[⬆ Back to Top](#table-of-contents)**

314. ### What are default values in destructuring assignment?
     A variable can be assigned a default value when the value unpacked from the array or object is undefined during destructuring assignment. It helps to avoid setting default values separately for each assignment. Let's take an example for both arrays and object usecases,

     **Arrays destructuring:**
     ```javascript
     var x, y, z;

     [x=2, y=4, z=6] = [10];
     console.log(x); // 10
     console.log(y); // 4
     console.log(z); // 6
     ```
     **Objects destructuring:**
     ```javascript
     var {x=2, y=4, z=6} = {x: 10};

     console.log(x); // 10
     console.log(y); // 4
     console.log(z); // 6
     ```

     **[⬆ Back to Top](#table-of-contents)**

315. ### How do you swap variables in destructuring assignment?
     If you don't use destructuring assignment, swapping two values requires a temporary variable. Whereas using destructuring feature, two variables values can be swapped in one destructuring expression. Let's swap two number variables in array destructuring assignment,
     ```javascript
     var x = 10, y = 20;

     [x, y] = [y, x];
     console.log(x); // 20
     console.log(y); // 10
     ```

     **[⬆ Back to Top](#table-of-contents)**

316. ### What are enhanced object literals?
     Object literals make it easy to quickly create objects with properties inside the curly braces. For example, it provides shorter syntax for common object property definition as below.
     ```javascript
     //ES6
     var x = 10, y = 20
     obj = { x, y }
     console.log(obj); // {x: 10, y:20}
     //ES5
     var x = 10, y = 20
     obj = { x : x, y : y}
     console.log(obj); // {x: 10, y:20}
     ```

     **[⬆ Back to Top](#table-of-contents)**

317. ### What are dynamic imports?
     The dynamic imports using `import()` function syntax allows us to load modules on demand by using promises or the async/await syntax. Currently this features is in stage4 proposal(https://github.com/tc39/proposal-dynamic-import). The main advantage of dynamic imports is reduction of our bundle's sizes, the size/payload response of our requests and overall improvements in the user experience.
     The syntax of dynamic imports would be as below,
     ```javascript
     import('./Module').then(Module => Module.method());
     ```

     **[⬆ Back to Top](#table-of-contents)**

318. ### What are the use cases for dynamic imports?
     Below are some of the use cases of using dynamic imports over static imports,
     1. Import a module on-demand or conditionally. For example, if you want to load a polyfill on legacy browser
     ```javascript
     if (isLegacyBrowser()) {
         import(···)
         .then(···);
     }
     ```
     2. Compute the module specifier at runtime. For example, you can use it for internationalization.
     ```javascript
     import(`messages_${getLocale()}.js`).then(···);
     ```
     3. Import a module from within a regular script instead a module.

     **[⬆ Back to Top](#table-of-contents)**

319. ### What are typed arrays?
     Typed arrays are array-like objects from ECMAScript 6 API for handling binary data. JavaScript provides 8 Typed array types,

     1. Int8Array: An array of 8-bit signed integers
     2. Int16Array: An array of 16-bit signed integers
     3. Int32Array: An array of 32-bit signed integers
     4. Uint8Array: An array of 8-bit unsigned integers
     5. Uint16Array: An array of 16-bit unsigned integers
     6. Uint32Array: An array of 32-bit unsigned integers
     7. Float32Array: An array of 32-bit floating point numbers
     8. Float64Array: An array of 64-bit floating point numbers

     For example, you can create an array of 8-bit signed integers as below

     ```javascript
     const a = new Int8Array();
     // You can pre-allocate n bytes
     const bytes = 1024
     const a = new Int8Array(bytes)
     ```

     **[⬆ Back to Top](#table-of-contents)**

320. ### What are the advantages of module loaders?
     The module loaders provides the below features,
     1. Dynamic loading
     2. State isolation
     3. Global namespace isolation
     4. Compilation hooks
     4. Nested virtualization

     **[⬆ Back to Top](#table-of-contents)**

321. ### What is collation?
     Collation is used for sorting a set of strings and searching within a set of strings. It is parameterized by locale and aware of Unicode. Let's take comparision and sorting features,
     1. **Comparison:**
     ```javascript
     var list = [ "ä", "a", "z" ]; // In German,  "ä" sorts with "a" Whereas in Swedish, "ä" sorts after "z"
     var l10nDE = new Intl.Collator("de");
     var l10nSV = new Intl.Collator("sv");
     console.log(l10nDE.compare("ä", "z") === -1); // true
     console.log(l10nSV.compare("ä", "z") === +1); // true
     ```
     2. **Sorting:**
     ```javascript
     var list = [ "ä", "a", "z" ]; // In German,  "ä" sorts with "a" Whereas in Swedish, "ä" sorts after "z"
     var l10nDE = new Intl.Collator("de");
     var l10nSV = new Intl.Collator("sv");
     console.log(list.sort(l10nDE.compare)) // [ "a", "ä", "z" ]
     console.log(list.sort(l10nSV.compare)) // [ "a", "z", "ä" ]
     ```

     **[⬆ Back to Top](#table-of-contents)**

322. ### What is for...of statement?
     The for...of statement creates a loop iterating over iterable objects or elements such as built-in String, Array, Array-like objects (like arguments or NodeList), TypedArray, Map, Set, and user-defined iterables. The basic usage of for...of statement on arrays would be as below,
     ```javascript
     let arrayIterable = [10, 20, 30, 40, 50];

     for (let value of arrayIterable) {
       value ++;
       console.log(value); // 11 21 31 41 51
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

323. ### What is the output of below spread operator array?
     ```javascript
     [...'John Resig']
     ```
     The output of the array is ['J', 'o', 'h', 'n', '', 'R', 'e', 's', 'i', 'g']
     **Explanation:** The string is an iterable type and the spread operator with in an array maps every character of an iterable to one element. Hence, each character of a string becomes an element within an Array.

     **[⬆ Back to Top](#table-of-contents)**

324. ### Is PostMessage secure?
     Yes, postMessages can be considered very secure as long as the programmer/developer is careful about checking the origin and source of an arriving message. But if you try to send/receive a message without verifying its source will create cross-site scripting attacks.

     **[⬆ Back to Top](#table-of-contents)**

325. ### What are the problems with postmessage target origin as wildcard?
     The second argument of postMessage method specifies which origin is allowed to receive the message. If you use the wildcard “*” as an argument then any origin is allowed to receive the message. In this case, there is no way for the sender window to know if the target window is at the target origin when sending the message. If the target window has been navigated to another origin, the other origin would receive the data. Hence, this may lead to XSS vulnerabilities.
     ```javascript
     targetWindow.postMessage(message, '*');
     ```

     **[⬆ Back to Top](#table-of-contents)**

326. ### How do you avoid receiving postMessages from attackers?
     Since the listener listens for any message, an attacker can trick the application by sending a message from the attacker’s origin,  which gives an impression that the receiver received the message from the actual sender’s window. You can avoid this issue by validating the origin of the message on the receiver's end using “message.origin” attribute. For examples, let's check the sender's origin(http://www.some-sender.com) on receiver side(www.some-receiver.com),
     ```javascript
     //Listener on http://www.some-receiver.com/
     window.addEventListener("message", function(message){
         if(/^http://www\.some-sender\.com$/.test(message.origin)){
              console.log('You recieved the data from valid sender', message.data);
        }
     });
     ```

     **[⬆ Back to Top](#table-of-contents)**

327. ### Can I avoid using postMessages completely?
     You cannot avoid using postMessages completely(or 100%). Even though your application doesn’t use postMessage considering the risks, a lot of third party scripts use postMessage to communicate with the third party service. So your application might be using postMessage without your knowledge.

     **[⬆ Back to Top](#table-of-contents)**

328. ### Is postMessages synchronous?
     The postMessages are synchronous in IE8 browser but they are asynchronous in IE9 and all other modern browsers (i.e, IE9+, Firefox, Chrome, Safari).Due to this asynchronous behaviour, we use a callback mechanism when the postMessage is returned.

     **[⬆ Back to Top](#table-of-contents)**

329. ### What paradigm is Javascript?
     JavaScript is a multi-paradigm language, supporting imperative/procedural programming, Object-Oriented Programming and functional programming. JavaScript supports Object-Oriented Programming with prototypical inheritance.

     **[⬆ Back to Top](#table-of-contents)**

330. ### What is the difference between internal and external javascript?
     **Internal JavaScript:** It is the source code with in the script tag.
     **External JavaScript:** The source code is stored in an external file(stored with .js extension) and referred with in the tag.

     **[⬆ Back to Top](#table-of-contents)**

331. ### Is JavaScript faster than server side script?
     Yes, JavaScript is than server side script. Because JavaScript is a client-side script it does require any web server’s help for its computation or calculation. So JavaScript is always faster than any server-side script like ASP, PHP, etc.

     **[⬆ Back to Top](#table-of-contents)**

332. ### How do you get the status of a checkbox?
     You can apply `checked` property on selected checkbox in the DOM. If the value is `True` means the checkbox is checked otherwise it is unchecked. For example, the below HTML checkbox element can be access using javascript as below,
     ```html
       <input type="checkbox" name="checkboxname" value="Agree"> Agree the conditions<br>
     ```
     ```javascript
     console.log(document.getElementById(‘checkboxname’).checked); // true or false
     ```

     **[⬆ Back to Top](#table-of-contents)**

333. ### What is the purpose of double tilde operator?
     The double tilde operator(~~) is known as double NOT bitwise operator. This operator is going to be a quicker substitute for Math.floor().

     **[⬆ Back to Top](#table-of-contents)**

334. ### How do you convert character to ASCII code?
     You can use `String.prototype.charCodeAt()` method to convert string characters to ASCII numbers. For example, let's find ASCII code for the first letter of 'ABC' string,
     ```javascript
     "ABC".charCodeAt(0) // returns 65
     ```
     Whereas `String.fromCharCode()` method to convert numbers to equal ASCII character.
     ```javascript
     String.fromCharCode(65,66,67); // returns 'ABC'
     ```

     **[⬆ Back to Top](#table-of-contents)**

335. ### What is ArrayBuffer?
     An ArrayBuffer object is used to represent a generic, fixed-length raw binary data buffer. You can create it as below,
     ```javascript
     let buffer = new ArrayBuffer(16); // create a buffer of length 16
     alert(buffer.byteLength); // 16
     ```
     To manipulate an ArrayBuffer, we need to use a “view” object.
     ```javascript
     //Create a DataView referring to the buffer
      let view = new DataView(buffer);
     ```

     **[⬆ Back to Top](#table-of-contents)**

336. ### What is the output of below string expression?
     ```javascript
     console.log("Welcome to JS world"[0])
     ```
     The output of the above expression is "W".
     **Explanation:** The bracket notation with specific index on a string returns the character at a specific location. Hence, it returns character "W" of the string. Since this is not supported in IE7 and below versions, you may need to use .charAt() method to get the desired result.

     **[⬆ Back to Top](#table-of-contents)**

337. ### What is the purpose of Error object?
     The Error constructor creates an error object and the instances of error objects are thrown when runtime errors occur. The Error object can also be used as a base object for user-defined exceptions. The syntax of error object would be as below,
     ```javascript
     new Error([message[, fileName[, lineNumber]]])
     ```
     You can throw user defined exceptions or errors using Error object in try...catch block as below,
     ```javascript
     try {
       if(withdraw > balance)
       throw new Error('Oops! You don't have enough balance');
     } catch (e) {
       console.log(e.name + ': ' + e.message);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

338. ### What is the purpose of EvalError object?
     The EvalError object indicates an error regarding the global `eval()` function. Even though this exception is not thrown by JavaScript anymore, the EvalError object remains for compatibility. The syntax of this expression would be as below,
     ```javascript
     new EvalError([message[, fileName[, lineNumber]]])
     ```
     You can throw EvalError with in try...catch block as below,
     ```javascript
     try {
       throw new EvalError('Eval function error', 'someFile.js', 100);
     } catch (e) {
       console.log(e.message, e.name, e.fileName);              // "Eval function error", "EvalError", "someFile.js"
     ```

     **[⬆ Back to Top](#table-of-contents)**

339. ### What are the list of cases error thrown from non-strict mode to strict mode?
     When you apply 'use strict'; syntax, some of the below cases will throw a SyntaxError before executing the script
     1. When you use Octal syntax
     ```javascript
     var n = 022;
     ```
     2. Using `with` statement
     3. When you use delete operator on a variable name
     4. Using eval or arguments as variable or function argument name
     5. When you use newly reserved keywords
     6. When you declare a function in a block
     ```javascript
     if (someCondition) { function f() {} }
     ```
     Hence, the errors from above cases helpful to avoid errors in development/production environments.

     **[⬆ Back to Top](#table-of-contents)**

340. ### Is all objects have prototypes?
     No. All objects have prototypes except for the base object which is created by the user, or an object that is created using the new keyword.

     **[⬆ Back to Top](#table-of-contents)**

341. ### What is the difference between a parameter and an argument?
     Parameter is the variable name of a function definition whereas an argument represent the value given to a function when it is invoked. Let's explain this with a simple function
     ```javascript
     function myFunction(parameter1, parameter2, parameter3) {
       console.log(arguments[0]) // "argument1"
       console.log(arguments[1]) // "argument2"
       console.log(arguments[2]) // "argument3"
     }
     myFunction("argument1", "argument2", "argument3")
     ```

     **[⬆ Back to Top](#table-of-contents)**

342. ### What is the purpose of some method in arrays?
     The some() method is used to test whether at least one element in the array passes the test implemented by the provided function. The method returns a boolean value. Let's take an example to test for any odd elements,
     ```javascript
     var array = [1, 2, 3, 4, 5, 6 ,7, 8, 9, 10];

     var odd = element ==> element % 2 !== 0;

     console.log(array.some(odd)); // true (the odd element exists)
     ```

     **[⬆ Back to Top](#table-of-contents)**

343. ### How do you combine two or more arrays?
     The concat() method is used to join two or more arrays by returning a new array containing all the elements. The syntax would be as below,
     ```javascript
     array1.concat(array2, array3, ..., arrayX)
     ```
     Let's take an example of array's concatenation with veggies and fruits arrays,
     ```javascript
       var veggies = ["Tomato", "Carrot", "Cabbage"];
       var fruits = ["Apple", "Orange", "Pears"];
       var veggiesAndFruits = veggies.concat(fruits);
       console.log(veggiesAndFruits); // Tomato, Carrot, Cabbage, Apple, Orange, Pears
     ```

     **[⬆ Back to Top](#table-of-contents)**

344. ### What is the difference between Shallow and Deep copy?
      There are two ways to copy an object,

      **Shallow Copy:**
      Shallow copy is a bit-wise copy of an object. A new object is created that has an exact copy of the values in the original object. If any of the fields of the object are references to other objects, just the reference addresses are copied i.e., only the memory address is copied.

      ### Example
      ```
      var empDetails = {
        name: "John", age: 25, expertise: "Software Developer"
      }
      ```
      to create a duplicate
      ```
      var empDetailsShallowCopy = empDetails    //Shallow copying!
      ```
      if we change some property value in the duplicate one like this:

      ```
      empDetailsShallowCopy.name = "Johnson"
      ```

      The above statement will also change the name of `empDetails`, since we have a shallow copy. That means we're loosing the original data as well.

      **Deep copy:**
      A deep copy copies all fields, and makes copies of dynamically allocated memory pointed to by the fields. A deep copy occurs when an object is copied along with the objects to which it refers.
      ### Example
      ```
      var empDetails = {
        name: "John", age: 25, expertise: "Software Developer"
      }
      ```
      Create a deep copy by using the properties from the original object into new variable

      ```
      var empDetailsDeepCopy = {
        name: empDetails.name,
        age: empDetails.age,
        expertise: empDetails.expertise
      }
      ```
      Now if you change `empDetailsDeepCopy.name`, it will only affect `empDetailsDeepCopy` & not `empDetails`

      **[⬆ Back to Top](#table-of-contents)**

345. ### How do you create specific number of copies of a string?
     The `repeat()` method is used to construct and returns a new string which contains the specified number of copies of the string on which it was called, concatenated together. Remember that this method has been added to the ECMAScript 2015 specification.
     Let's take an example of Hello string to repeat it 4 times,
     ```javascript
     'Hello'.repeat(4);  // 'HelloHelloHelloHello'
     ```
346. ### How do you return all matching strings against a regular expression?
     The `matchAll()` method can be used to return an iterator of all results matching a string against a regular expression. For example, the below example returns an array of matching string results against a regular expression,
     ```javascript
     let regexp = /Hello(\d?))/g;
     let greeting = 'Hello1Hello2Hello3';

     let greetingList = [...greeting.matchAll(regexp)];

     console.log(greetingList[0]); //Hello1
     console.log(greetingList[1]); //Hello2
     console.log(greetingList[2]); //Hello3
     ```

     **[⬆ Back to Top](#table-of-contents)**

347. ### How do you trim a string at the beginning or ending?
     The `trim` method of string prototype is used to trim on both sides of a string. But if you want to trim especially at the beginning or ending of the string then you can use `trimStart/trimLeft` and `trimEnd/trimRight` methods. Let's see an example of these methods on a greeting message,
     ```javascript
     var greeting = '   Hello, Goodmorning!   ';

     console.log(greeting); // "   Hello, Goodmorning!   "
     console.log(greeting.trimStart()); // "Hello, Goodmorning!   "
     console.log(greeting.trimLeft()); // "Hello, Goodmorning!   "

     console.log(greeting.trimEnd()); // "   Hello, Goodmorning!"
     console.log(greeting.trimRight()); // "   Hello, Goodmorning!"
     ```

     **[⬆ Back to Top](#table-of-contents)**

348. ### What is the output of below console statement with unary operator?
     Let's take console statement with unary operator as given below,
     ```javascript
     console.log(+ 'Hello');
     ```
     The output of the above console log statement returns NaN. Because the element is prefixed by the unary operator and the JavaScript interpreter will try to convert that element into a number type. Since the conversion fails, the value of the statement results in NaN value.

     **[⬆ Back to Top](#table-of-contents)**

349. ### Does javascript uses mixins?
     **[⬆ Back to Top](#table-of-contents)**
350. ### What is a thunk function?
     A thunk is just a function which delays the evaluation of the value. It doesn’t take any arguments but gives the value whenever you invoke the thunk. i.e, It is used not to execute now but it will be sometime in the future. Let's take a synchronous example,
     ```javascript
     const add = (x,y) => x + y;

     const thunk = () => add(2,3);

     thunk() // 5
     ```
     **[⬆ Back to Top](#table-of-contents)**

351. ### What are asynchronous thunks?
     The asynchronous thunks are useful to make network requests.  Let's see an example of network requests,
     ```javascript
     function fetchData(fn){
       fetch('https://jsonplaceholder.typicode.com/todos/1')
       .then(response => response.json())
       .then(json => fn(json))
     }


     const asyncThunk = function (){
        return fetchData(function getData(data){
           console.log(data)
       })
     }

     asyncThunk()
     ```
     The `getData` function won't be called immediately but it will be invoked only when the data is available from API endpoint. The setTimeout function is also used to make our code asynchronous. The best real time example is redux state management library which uses the asynchronous thunks to delay the actions to dispatch.

     **[⬆ Back to Top](#table-of-contents)**

352. ### What is the output of below function calls?
     **Code snippet:**
     const circle = {
       radius: 20,
       diameter() {
         return this.radius * 2;
       },
       perimeter: () => 2 * Math.PI * this.radius
     };

     console.log(circle.diameter());
     console.log(circle.perimeter());

     **Output:**

     The output is 40 and NaN. Remember that diameter is a regular function, whereas the value of perimeter is an arrow function. The this keyword of a regular function(i.e, diameter) refers to surrounding scope which is a class(i.e, Shape object). Whereas this keyword of perimeter function refers the surrounding scope which is window object. Since there is no radius property on window object it returns an undefined value and the multiple of number value returns NaN value.

     **[⬆ Back to Top](#table-of-contents)**

353. ### How to remove all line breaks from a string?
     The easiest approach is using regular expressions to detect and replace newlines in the string. In this case, we use replace function along with string to replace with, which in our case is an empty string.
     ```javascript
     function remove_linebreaks( var message ) {
         return message.replace( /[\r\n]+/gm, "" );
     }
     ```
     In the above expression, g and m are for global and multiline flags.

     **[⬆ Back to Top](#table-of-contents)**
     
354. ### What is the difference between reflow and repaint?
     A *repaint* occurs when changes are made which affect the visibility of an element, but not its layout. Examples of this include outline, visibility, or background color. A *reflow* involves changes that affect the layout of a portion of the page (or the whole page). Resizing the browser window, changing the font, content changing (such as user typing text), using JavaScript methods involving computed styles, adding or removing elements from the DOM, and changing an element's classes are a few of the things that can trigger reflow. Reflow of an element causes the subsequent reflow of all child and ancestor elements as well as any elements following it in the DOM.

      **[⬆ Back to Top](#table-of-contents)**

355. ### What happens with negating an array?
     Negating an array with `!` character will coerce the array into a boolean. Since Arrays are considered to be truthy So negating it will return `false`.
     ```javascript
     console.log(![]); // false
     ```
     **[⬆ Back to Top](#table-of-contents)**
356. ### What happens if we add two arrays?
     If you add two arrays together, it will convert them both to strings and concatenate them. For example, the result of adding arrays would be as below,
     ```javascript
     console.log(['a'] + ['b']);  // "ab"
     console.log([] + []); // ""
     console.log(![] + []); // "false", because ![] returns false.
     ```
     **[⬆ Back to Top](#table-of-contents)**

357. ### What is the output of prepend additive operator on falsy values?
     If you prepend additive(+) operator on falsy values(null, undefined, NaN, false, ""), the falsy value converts to a number value zero. Let's display them on browser console as below,
     ```javascript
     console.log(+null); // 0
     console.log(+undefined);// 0
     console.log(+false); // 0
     console.log(+NaN); // 0
     console.log(+""); // 0
     ```

     **[⬆ Back to Top](#table-of-contents)**

358. ### How do you create self string using special characters?
     The self string can be formed with the combination of `[]()!+` characters. You need to remember the below conventions to achieve this pattern.
     1. Since Arrays are truthful values, negating the arrays will produce false: ![] === false
     2. As per JavaScript coercing rules, the addition of arrays together will toString them: [] + [] === ""
     3. Prepend an array with + operator will convert an array to false, the negation will make it true and finally converting the result will produce value '1': +(!(+[])) === 1

     By applying the above rules, we can derive below conditions
     ```javascript
     ![] + [] === "false"
     +!+[] === 1
     ```
     Now the character pattern would be created as below,

     ```javascript
           s               e               l               f
      ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^

      (![] + [])[3] + (![] + [])[4] + (![] + [])[2] + (![] + [])[0]
      ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^
     (![] + [])[+!+[]+!+[]+!+[]] +
     (![] + [])[+!+[]+!+[]+!+[]+!+[]] +
     (![] + [])[+!+[]+!+[]] +
     (![] + [])[+[]]
     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
     (![]+[])[+!+[]+!+[]+!+[]]+(![]+[])[+!+[]+!+[]+!+[]+!+[]]+(![]+[])[+!+[]+!+[]]+(![]+[])[+[]]
     ```
     **[⬆ Back to Top](#table-of-contents)**

358. ### How do you remove falsy values from an array?
     You can apply filter method on array by passing Boolean as parameter. This way it removes all falsy values(0, undefined, null, false and "") from the array.
     ```javascript
     const myArray = [false, null, 1,5, undefined]
     myArray.filter(Boolean); // [1, 5] // is same as myArray.filter(x => x);
     ```

     **[⬆ Back to Top](#table-of-contents)**

359. ### How do you get unique values of an array?
     You can get unique values of an array with the combination of `Set` and rest expression/spread(...) syntax.
     ```javascript
     console.log([...new Set([1, 2, 4, 4, 3])]); // [1, 2, 4, 3]
     ```

     **[⬆ Back to Top](#table-of-contents)**

360. ### What is destructuring aliases?
     Sometimes you would like to have destructured variable with a different name than the property name. In that case, you'll use a `: newName` to specify a name for the variable. This process is called destructuring aliases.
     ```javascript
     const obj = { x: 1 };
     // Grabs obj.x as as { otherName }
     const { x: otherName } = obj;
     ```

     **[⬆ Back to Top](#table-of-contents)**

361. ### How do you map the array values without using map method?
     You can map the array values without using `map` method by just using `from` method of Array. Let's map city names from Countries array,
     ```javascrippt
     const countries = [
         { name: 'India', capital: 'Delhi' },
         { name: 'US', capital: 'Washington' },
         { name: 'Russia', capital: 'Moscow' },
         { name: 'Singapore', capital: 'Singapore' },
         { name: 'China', capital: 'Beijing' },
         { name: 'France', capital: 'Paris' },
     ];

     const cityNames = Array.from(countries, ({ capital}) => capital);
     console.log(cityNames); // ['Delhi, 'Washington', 'Moscow', 'Singapore', 'Beijing', 'Paris']
     ```

     **[⬆ Back to Top](#table-of-contents)**

362. ### How do you empty an array?
     You can empty an array quicky by setting the array length to zero.
     ```javascript
     let cities = ['Singapore', 'Delhi', 'London'];
     cities.length = 0; // cities becomes []
     ```

     **[⬆ Back to Top](#table-of-contents)**

363. ### How do you rounding numbers to certain decimals?
     You can rounding numbers to a certain number of decimals using `toFixed` method from native javascript.
     ```javascript
     let pie = 3.141592653;
     pie = pie.toFixed(3); // 3.142
     ```

     **[⬆ Back to Top](#table-of-contents)**

364. ### What is the easiest way to convert an array to an object?
     You can convert an array to an object with the same data using spread(...) operator.
     ```javascript
     var fruits = ["banana", "apple", "orange", "watermelon"];
     var fruitsObject = {...fruits};
     console.log(fruitsObject); // {0: "banana", 1: "apple", 2: "orange", 3: "watermelon"}
     ```

     **[⬆ Back to Top](#table-of-contents)**

365. ### How do you create an array with some data?
     You can create an array with some data or an array with the same values using `fill` method.
     ```javascript
     var newArray = new Array(5).fill("0");
     console.log(newArray); // ["0", "0", "0", "0", "0"]
     ```

     **[⬆ Back to Top](#table-of-contents)**

366. ### What are the placeholders from console object?
     Below are the list of placeholders available from console object,
     1. %o — It takes an object,
     2. %s — It takes a string,
     3. %d — It is used for a decimal or integer
     These placeholders can be represented in the console.log as below
     ```javascript
     const user = { "name":"John", "id": 1, "city": "Delhi"};
     console.log("Hello %s, your details %o are available in the object form", "John", user); // Hello John, your details {name: "John", id: 1, city: "Delhi"} are available in object
     ```

     **[⬆ Back to Top](#table-of-contents)**

367. ### Is it possible to add CSS to console messages?
     Yes, you can apply CSS styles to console messages similar to html text on the web page.
     ```javascript
     console.log('%c The text has blue color, with large font and red background', 'color: blue; font-size: x-large; background: red');
     ```
     The text will be displayed as below,

     ![Screenshot](images/console-css.png)

     **Note:** All CSS styles can be applied to console messages.

     **[⬆ Back to Top](#table-of-contents)**

368. ### What is the purpose of dir method of console object?
     The `console.dir()` is used to display an interactive list of the properties of the specified JavaScript object as JSON.
     ```javascript
     const user = { "name":"John", "id": 1, "city": "Delhi"};
     console.dir(user);
     ```
     The user object displayed in JSON representation
     ![Screenshot](images/console-css.png)

     **[⬆ Back to Top](#table-of-contents)**

369. ### Is it possible to debug HTML elements in console?
     Yes, it is possible to get and debug HTML elements in the console just like inspecting elements.
     ```javascript
     const element = document.getElementsByTagName("body")[0];
     console.log(element);
     ```
     It prints the HTML element in the console
     ![Screenshot](images/console-html.png)

     **[⬆ Back to Top](#table-of-contents)**

370. ### How do you display data in a tabular format using console object?
     The `console.table()` is used to display data in the console in a tabular format to visualize complex arrays or objects.
     ```javascript
     const users = [{ "name":"John", "id": 1, "city": "Delhi"},
                   { "name":"Max", "id": 2, "city": "London"},
                   { "name":"Rod", "id": 3, "city": "Paris"}];
     console.table(users);
     ```
     The data visualized in a table format
     ![Screenshot](images/console-table.png)
     **Not:** Remember that `console.table()` is not supported in IE.

     **[⬆ Back to Top](#table-of-contents)**

371. ### How do you verify that an argument is a Number or not?
     The combination of IsNaN and isFinite methods are used to confirm whether an argument is a number or not.
     ```javascript
     function isNumber(n){
         return !isNaN(parseFloat(n)) && isFinite(n);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

372. ### How do you create copy to clipboard button?
     You need to select the content(using .select() method) of input element and execute the copy command with execCommand (i.e, execCommand('copy')). You can also execute another system commands like cut and paste.
     ```javascript
     document.querySelector("#copy-button").onclick = function() {
       // Select the content
       document.querySelector("#copy-input").select();
       // Copy to the clipboard
       document.execCommand('copy');
     };

     ```

     **[⬆ Back to Top](#table-of-contents)**

373. ### What is the shortcut to get timestamp?
     You can use `new Date().getTime()` to get the current timestamp. There is an alternative shortcut to get the value.
     ```javascript
     console.log(+new Date());
     console.log(Date.now());
     ```

     **[⬆ Back to Top](#table-of-contents)**

374. ### How do you flattening multi dimensional arrays?
     Flattening bi-dimensional arrays is trivial with Spread operator.
     ```javascript
     const biDimensionalArr = [11, [22, 33], [44, 55], [66, 77], 88, 99];
     const flattenArr = [].concat(...biDimensionalArr); // [11, 22, 33, 44, 55, 66, 77, 88, 99]
     ```
     But you can make it work with multi-dimensional arrays by recursive calls,

     ```javascript
     function flattenMultiArray(arr) {
         const flattened = [].concat(...arr);
         return flattened.some(item => Array.isArray(item)) ? flattenMultiArray(flattened) : flattened;
      }
     const multiDimensionalArr = [11, [22, 33], [44, [55, 66, [77, [88]], 99]]];
     const flatArr = flattenMultiArray(multiDimensionalArr); // [11, 22, 33, 44, 55, 66, 77, 88, 99]
     ```

     **[⬆ Back to Top](#table-of-contents)**

375. ### What is the easiest multi condition checking?

     You can use `indexOf` to compare input with multiple values instead of checking each value as one condition.
     ```javascript
     // Verbose approach
     if (input === 'first' || input === 1 || input === 'second' || input === 2) {
       someFunction();
     }
     // Shortcut
     if (['first', 1, 'second', 2].indexOf(input) !== -1) {
       someFunction();
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

376. ### How do you capture browser back button?
     The `window.onbeforeunload` method is used to capture browser back button event. This is helpful to warn user about loosing the current data.
     ```javascript
     window.onbeforeunload = function() {
     	alert("You work will be lost");
     };
     ```

     **[⬆ Back to Top](#table-of-contents)**

377. ### How do you disable right click in the web page?
     The right click on the page can be disabled by returning false from `oncontextmenu` attribute on body element.
     ```html
     <body oncontextmenu="return false;">
     ```

     **[⬆ Back to Top](#table-of-contents)**

378. ### What are wrapper objects?
     Primitive Values like string,number and boolean don't have properties and methods but they are temporarily converted or coerce to an object(Wrapper object) when you try to perform actions on them. For example, if you apply toUpperCase() method on a primitive string value, it does not throw an error but returns uppercase of the string.
     ```javascript
     let name = "john";

     console.log(name.toUpperCase());  // Behind the scenes treated as console.log(new String(name).toUpperCase());
     ```
     i.e, Every primitive except null and undefined have Wrapper Objects and the list of wrapper objects are are String,Number,Boolean,Symbol and BigInt.
     **[⬆ Back to Top](#table-of-contents)**

379. ### What is AJAX?
     AJAX stands for Asynchronous JavaScript and XML and it is a group of related technologies(HTML, CSS, JavaScript, XMLHttpRequest API etc) used to display data asynchronously. i.e. We can send data to the server and get data from the server without reloading the web page.

     **[⬆ Back to Top](#table-of-contents)**

380. ### What are the different ways to deal with Asynchronous Code?
     Below are the list of different way to deal with Asynchronous code.
     1. Callbacks
     2. Promises
     3. Async/await
     4. Third-party libraries such as async.js,bluebird etc

     **[⬆ Back to Top](#table-of-contents)**

381. ### How to cancel a fetch request?
     Until few days back, One shortcoming of native promises is no direct way to cancel a fetch request. But the new `AbortController` from js specification allows you to use a signal to abort one or multiple fetch calls.
     The basic flow of cancelling a fetch request would be as below,
     1. Create an `AbortController` instance
     2. Get the signal property of an instance and pass the signal as a fetch option for signal
     3. Call the AbortController's abort property to cancel all fetches that use that signal
     For example, let's pass the same signal to multiple fetch calls will cancel all requests with that signal,
     ```js
     const controller = new AbortController();
     const { signal } = controller;

     fetch("http://localhost:8000", { signal }).then(response => {
         console.log(`Request 1 is complete!`);
     }).catch(e => {
         if(e.name === "AbortError") {
             // We know it's been canceled!
         }
     });

     fetch("http://localhost:8000", { signal }).then(response => {
         console.log(`Request 2 is complete!`);
     }).catch(e => {
          if(e.name === "AbortError") {
              // We know it's been canceled!
           }
     });

     // Wait 2 seconds to abort both requests
     setTimeout(() => controller.abort(), 2000);
     ```
     **[⬆ Back to Top](#table-of-contents)**

382. ### What is web speech API?
     Web speech API is used to enable modern browsers recognize and synthesize speech(i.e, voice data into web apps). This API has been introduced by W3C Community in the year 2012. It has two main parts,
     1. **SpeechRecognition (Asynchronous Speech Recognition or Speech-to-Text):** It provides the ability to recognize voice context from an audio input and respond accordingly. This is accessed by `SpeechRecognition` interface.
     The below example shows on how to use this API to get text from speech,
     ```js
     window.SpeechRecognition = window.webkitSpeechRecognition || window.SpeechRecognition;  // webkitSpeechRecognition for Chrome and SpeechRecognition for FF
     const recognition = new window.SpeechRecognition();
     recognition.onresult = (event) => { // SpeechRecognitionEvent type
       const speechToText = event.results[0][0].transcript;
       console.log(speechToText);
     }
     recognition.start();
     ```
     In this API, browser is going to ask you for permission to use your microphone
     2. **SpeechSynthesis (Text-to-Speech):** It provides the ability to recognize voice context from an audio input and respond. This is accessed by `SpeechSynthesis` interface.
     For example, the below code is used to get voice/speech from text,
     ```js
     if('speechSynthesis' in window){
         var speech = new SpeechSynthesisUtterance('Hello World!');
         speech.lang = 'en-US';
         window.speechSynthesis.speak(speech);
     }
     ```
     The above examples can be tested on chrome(33+) browser's developer console.
     **Note:**  This API is still a working draft and only available in Chrome and Firefox browsers(ofcourse Chrome only implemented the specification)
     **[⬆ Back to Top](#table-of-contents)**

383. ### What is minimum timeout throttling?
     Both browser and NodeJS javascript environments, throttles with a minimum delay that is greater than 0ms. That means even though setting a delay of 0ms will not happen instantaneously.
     **Browsers:** They have minimum delay of 4ms. This throttle occurs when successive calls are triggered due to callback nesting(certain depth) or after a certain number of successive intervals.
     Note: The older browsers has minimum delay of 10ms.
     **Nodejs:** They have minimum delay of 1ms. This throttle happens when delay is larger than 2147483647 or less than 1.
     The best example to explain this timeout throttling behavior is the order of below code snippet.
     ```js
     function runMeFirst() {
         console.log('My script is initialized');
     }
     setTimeout(runMeFirst, 0);
     console.log('Script loaded');
     ```
     and the output would be in
     ```cmd
     Script loaded
     My script is initialized
     ```
     If you don't use `setTimeout`, the order of logs will be in sequential.
     ```js
     function runMeFirst() {
        console.log('My script is initialized');
     }
     runMeFirst();
     console.log('Script loaded');
     ```
     and the output is,
     ```cmd
     My script is initialized
     Script loaded
     ```
     **[⬆ Back to Top](#table-of-contents)**

384. ### How do you implement zero timeout in modern browsers?
     You can't use setTimeout(fn, 0) to execute the code immediately due to minimum delay of greater than 0ms. But you can use window.postMessage() to achieve this behavior.

     **[⬆ Back to Top](#table-of-contents)**

385. ### What are tasks in event loop?
     A task is any javascript code/program which is scheduled to be run by the standard mechanisms such as initially starting to run a program, run an event callback, or an interval or timeout being fired. All these tasks are schedules on task queue.
     Below are the list of use cases to add tasks to the task queue,
     1. When a new javascript program is executed directly from console or running by the <script> element, the task will be added to task queue.
     2. When an event fires, the event callback added to task queue
     3. When a setTimeout or setInterval is reached, the corresponding callback added to task queue

     **[⬆ Back to Top](#table-of-contents)**

386. ### What is microtask?
     Microtask is the javascript code which needs to be executed immediately after the currently executing task/microtask is completed. They are kind of blocking in nature. i.e, The main thread will be blocked until microtask queue is empty.
     The main sources of microtasks are Promise.resolve, Promise.reject, MutationObservers, IntersectionObservers etc

     **Note:** All of these microtasks are processed in the same turn of event loop.
     **[⬆ Back to Top](#table-of-contents)**

387. ### What are different event loops?


     **[⬆ Back to Top](#table-of-contents)**

388. ### What is the purpose of queueMicrotask?

     **[⬆ Back to Top](#table-of-contents)**

389. ### How do you use javascript libraries in typescript file?
     It is known that not all JavaScript libraries or frameworks have TypeScript declaration files. But if you still want to use libraries or frameworks in our TypeScript files without getting compilation errors, the only solution is `declare` keyword along with a variable declaration. For example, let's imagine you have a library called `customLibrary` that doesn’t have a TypeScript declaration and have a namespace called `customLibrary` in the global namespace. You can use this library in typescript code as below,
     ```js
     declare var customLibrary;
     ```
     In the runtime, typescript will provide the type to `customLibrary` variable as `any` type. The another alternative without using declare keyword is below
     ```js
     var customLibrary: any;
     ```
     **[⬆ Back to Top](#table-of-contents)**

390. ### What are the differences between promises and observables?
     Some of the major difference in a tabular form

     | Promises | Observables |
     |---- | ---------
     | Emits only a single value at a time  | Emits multiple values over a period of time(stream of values ranging from 0 to multiple) |
     | Eager in nature; they are going to be called immediately  | Lazy in nature; they require subscription to be invoked |
     | Promise is always asynchronous even though it resolved immediately | Observable can be either synchronous or asynchronous|
     | Doesn't provide any operators | Provides operators such as map, forEach, filter, reduce, retry, and retryWhen etc |
     | Cannot be canceled | Canceled by using unsubscribe() method |

     **[⬆ Back to Top](#table-of-contents)**

391. ### What is heap?
     Heap(Or memory heap) is the memory location where objects are stored when we define variables. i.e, This is the place where all the memory allocations and de-allocation take place. Both heap and call-stack are two containers of JS runtime.
     Whenever runtime comes across variables and function declarations in the code it stores them in the Heap.

     ![Screenshot](images/heap.png)

     **[⬆ Back to Top](#table-of-contents)**

392. ### What is an event table?
     Event Table is a data structure that stores and keeps track of all the events which will be executed asynchronously like after some time interval or after the resolution of some API requests. i.e Whenever you call a setTimeout function or invoke async operation, it is added to the Event Table.
     It doesn't not execute functions on it’s own. The main purpose of event table is to keep track of events and send them to the Event Queue as shown in the below diagram.

     ![Screenshot](images/event-table.png)

     **[⬆ Back to Top](#table-of-contents)**

393. ### What is a microTask queue?
     Microtask Queue is the new queue where all the tasks initiated by promise objects get processed before the callback queue.
     The microtasks queue are processed before the next rendering and painting jobs. But if these microtasks are running for long time then it leads to visual degradation.

     **[⬆ Back to Top](#table-of-contents)**

394. ### What is the difference between shim and polyfill?
     A shim is a library that brings a new API to an older environment, using only the means of that environment.  It isn't necessarily restricted to a web application. For example, es5-shim.js is used to emulate ES5 features on older browsers (mainly pre IE9).
     Whereas polyfill is a piece of code (or plugin) that provides the technology that you, the developer, expect the browser to provide natively.
     In a simple sentence, A polyfill is a shim for a browser API.

     **[⬆ Back to Top](#table-of-contents)**

395. ### How do you detect primitive or non primitive value type?
     In JavaScript, primitive types include boolean, string, number, BigInt, null, Symbol and undefined. Whereas non-primitive types include the Objects. But you can easily identify them with the below function,
     ```js
     var myPrimitive = 30;
     var myNonPrimitive = {};
     function isPrimitive(val) {
         return Object(val) !== val;
     }

     isPrimitive(myPrimitive);
     isPrimitive(myNonPrimitive);
     ```
     If the value is a primitive data type, the Object constructor creates a new wrapper object for the value. But If the value is a non-primitive data type (an object), the Object constructor will give the same object.

     **[⬆ Back to Top](#table-of-contents)**

396. ### What is babel?
     Babel is a JavaScript transpiler to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments. Some of the main features are listed below,
     1. Transform syntax
     2. Polyfill features that are missing in your target environment (using @babel/polyfill)
     3. Source code transformations (or codemods)

     **[⬆ Back to Top](#table-of-contents)**

397. ### Is Node.js completely single threaded?
     Node is single thread, but some of the functions included in the Node.js standard library(e.g, fs module functions) are not single threaded. i.e, Their logic runs outside of the Node.js single thread to improve the speed and peformance of a program.

     **[⬆ Back to Top](#table-of-contents)**

398. ### What are the common use cases of observables?
     Some of the most common use cases of observables are web sockets with push notifications, user input changes, repeating intervals, etc

     **[⬆ Back to Top](#table-of-contents)**

399. ### What is RxJS?
     RxJS (Reactive Extensions for JavaScript) is a library for implementing reactive programming using observables that makes it easier to compose asynchronous or callback-based code. It also provides utility functions for creating and working with observables.

     **[⬆ Back to Top](#table-of-contents)**

400. ### What is the difference between Function constructor and function declaration?
     The functions which are created with `Function constructor` do not create closures to their creation contexts but they are always created in the global scope. i.e, the function can access own local variables and global scope variables only. Whereas function declarations can access outer function variables(closures) too.

     Let's see this difference with an example,

     **Function Constructor:**
     ```js
     var a = 100;
     function createFunction() {
         var a = 200;
         return new Function('return a;');
     }
     console.log(createFunction()()); // 100
     ```
     **Function declaration:**
     ```js
     var a = 100;
     function createFunction() {
         var a = 200;
         return function func() {
             return a;
         }
     }
     console.log(createFunction()()); // 200
     ```

     **[⬆ Back to Top](#table-of-contents)**

401. ### What is a Short circuit condition?
     Short circuit conditions are meant for condensed way of writing simple if statements. Let's demonstrate the scenario using an example. If you would like to login to a portal with an authentication condition, the expression would be as below,
     ```js
     if (authenticate) {
        loginToPorta();
     }
     ```
     Since the javascript logical operators evaluates from left to right, the above expression can be simplified using && logical operator
     ```js
     authenticate && loginToPorta();
     ```
     **[⬆ Back to Top](#table-of-contents)**

402. ### What is the easiest way to resize an array?
     The length property of array is useful to resize or empty an array quickly. Let's apply length property on number array to resize the number of elements from 5 to 2,
     ```js
     var array = [1, 2, 3, 4, 5];
     console.log(array.length); // 5

     array.length = 2;
     console.log(array.length); // 2
     console.log(array); // [1,2]
     ```
     and the array can be emptied too
     ```js
     var array = [1, 2, 3, 4, 5];
     array.length = 0;
     console.log(array.length); // 0
     console.log(array); // []
     ```
     **[⬆ Back to Top](#table-of-contents)**

403. ### What is an observable?
     An Observable is basically a function that can return a stream of values either synchronously or asynchronously to an observer over time. The consumer can get the value by calling `subscribe()` method.
     Let's look at a simple example of an Observable
     ```js
     import { Observable } from 'rxjs';

     const observable = new Observable(observer => {
       setTimeout(() => {
         observer.next('Message from a Observable!');
       }, 3000);
     });

     observable.subscribe(value => console.log(value));
     ```
     ![Screenshot](images/observables.png)

     **Note:** Observables are not part of the JavaScript language yet but they are being proposed to be added to the language

     **[⬆ Back to Top](#table-of-contents)**

404. ### What is the difference between function and class declarations?
     The main difference between function declarations and class declarations is `hoisting`. The function declarations are hoisted but not class declarations.
     **Classes:**
     ```js
     const user = new User(); // ReferenceError

     class User {}
     ```
     **Constructor Function:**
     ```js
      const user = new User(); // No error

      function User() {
      }
     ```

     **[⬆ Back to Top](#table-of-contents)**

405. ### What is an async function?
     An async function is a function declared with the `async` keyword which enable asynchronous, promise-based behavior to be written in a cleaner style by avoiding promise chains. These functions can contain zero or more `await` expressions.

     Let's take a below async function example,

     ```js
     async function logger() {

       let data = await fetch('http://someapi.com/users'); // pause until fetch returns
       console.log(data)
     }
     logger();
     ```
     It is basically syntax sugar over ES2015 promises and generators.

     **[⬆ Back to Top](#table-of-contents)**

406. ### How do you prevent promises swallowing errors?
     While using asynchronous code, JavaScript’s ES6 promises can make your life a lot easier without having callback pyramids and error handling on every second line. But Promises have some pitfalls and the biggest one is swallowing errors by default.

     Let's say you expect to print an error to the console for all the below cases,

         ```js
         Promise.resolve('promised value').then(function() {
             throw new Error('error');
         });

         Promise.reject('error value').catch(function() {
             throw new Error('error');
         });

         new Promise(function(resolve, reject) {
             throw new Error('error');
         });
         ```

        But there are many modern JavaScript environments won’t print any errors. You can fix this problem in different ways,

     1. **Add catch block at the end of each chain:** You can add catch block to the end of each of your promise chains

         ```js
         Promise.resolve('promised value').then(function() {
             throw new Error('error');
         }).catch(function(error) {
           console.error(error.stack);
         });
          ```

        But it is quite difficult to type for each promise chain and verbose too.

     2. **Add done method:** You can replace first solution's then and catch blocks with done method

         ```js
         Promise.resolve('promised value').done(function() {
             throw new Error('error');
         });
         ```

        Let's say you want to fetch data using HTTP and later perform processing on the resulted data asynchronously. You can write `done` block as below,

         ```js
         getDataFromHttp()
           .then(function(result) {
             return processDataAsync(result);
           })
           .done(function(processed) {
             displayData(processed);
           });
         ```

         In future, if the processing library API changed to synchronous then you can remove `done` block as below,

         ```js
          getDataFromHttp()
            .then(function(result) {
              return displayData(processDataAsync(result));
            })
         ```

         and then you forgot to add `done` block to `then` block leads to silent errors.

     3. **Extend ES6 Promises by Bluebird:**
         Bluebird extends the ES6 Promises API to avoid the issue in second solution. This library has a “default” onRejection handler which will print all errors from rejected Promises to stderr. After installation, you can process unhandled rejections

         ```js
         Promise.onPossiblyUnhandledRejection(function(error){
             throw error;
         });
         ```

         and discard a rejection, just handle it with an empty catch

         ```js
         Promise.reject('error value').catch(function() {});
         ```

     **[⬆ Back to Top](#table-of-contents)**

407. ### What is deno?
     Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 JavaScript engine and the Rust programming language.

     **[⬆ Back to Top](#table-of-contents)**

408. ### How do you make an object iterable in javascript?
     By default, plain object is not iterable. But you can make the object iterable by defining a `Symbol.iterator` property on it.

     Let's demonstrate this with an example,

     ```js
     const collection = {
       one: 1,
       two: 2,
       three: 3,
       [Symbol.iterator]() {
         const values = Object.keys(this);
         let i = 0;
         return {
           next: () => {
             return {
               value: this[values[i++]],
               done: i > values.length
             }
           }
         };
       }
     };

     const iterator = collection[Symbol.iterator]();

     console.log(iterator.next());    // → {value: 1, done: false}
     console.log(iterator.next());    // → {value: 2, done: false}
     console.log(iterator.next());    // → {value: 3, done: false}
     console.log(iterator.next());    // → {value: undefined, done: true}
     ```

     The above process can be simplified using a generator function,

     ```js
     ```

     **[⬆ Back to Top](#table-of-contents)**

409. ### What is a Proper Tail Call?
     First, we should know about tail call before talking about "Proper Tail Call". A tail call is a subroutine or function call performed as the final action of a calling function. Whereas **Proper tail call(PTC)** is a technique where the program or code will not create additional stack frames for a recursion when the function call is a tail call.

     For example, the below classic or head recursion of factorial function relies on stack for each step. Each step need to be processed upto `n * factorial(n - 1)`

     ```js
     function factorial(n) {
       if (n === 0) {
         return 1
       }
       return n * factorial(n - 1)
     }
     console.log(factorial(5)); //120
     ```

     But if you use Tail recursion functions, they keep passing all the necessary data it needs down the recursion without relying on the stack.

     ```js
     function factorial(n, acc = 1) {
       if (n === 0) {
         return acc
       }
       return factorial(n - 1, n * acc)
     }
     console.log(factorial(5)); //120
     ```

     The above pattern returns the same output as first one. But the accumulator keeps track of total as an argument without using stack memory on recursive calls.

     **[⬆ Back to Top](#table-of-contents)**

410. ### How do you check an object is a promise or not?

  If you don't know if a value is a promise or not, wrapping the value as `Promise.resolve(value)` which returns a promise

     ```js
        function isPromise(object){
          if(Promise && Promise.resolve){
            return Promise.resolve(object) == object;
          }else{
            throw "Promise not supported in your environment"
          }
        }

        var i = 1;
        var promise = new Promise(function(resolve,reject){
          resolve()
        });

        console.log(isPromise(i)); // false
        console.log(isPromise(p)); // true
    ```

   Another way is to check for `.then()` handler type

   ```js
    function isPromise(value) {
      return Boolean(value && typeof value.then === 'function');
    }
    var i = 1;
    var promise = new Promise(function(resolve,reject){
      resolve()
    });

    console.log(isPromise(i)) // false
    console.log(isPromise(promise)); // true
   ```


    **[⬆ Back to Top](#table-of-contents)**

411. ### How to detect if a function is called as constructor?
     You can use `new.target` pseudo-property to detect whether a function was called as constructor(using the new operator) or as regular function call.

     1. If a constructor or function invoked using the new operator, new.target returns a reference to the constructor or function.
     2. For function calls, new.target is undefined.

     ```js
     function Myfunc() {
         if (new.target) {
            console.log('called with new');
         } else {
            console.log('not called with new');
         }
     }

     new Myfunc(); // called with new
     Myfunc(); // not called with new
     Myfunc.call({}); not called with new
     ```


     **[⬆ Back to Top](#table-of-contents)**

### Coding Exercise

#### 1. What is the output of below code?

```javascript
var car = new Vehicle("Honda", "white", "2010", "UK");
console.log(car);

function Vehicle(model, color, year, country) {
    this.model = model;
    this.color = color;
    this.year = year;
    this.country = country;
}
```

- 1: Undefined
- 2: ReferenceError
- 3: null
- 4: {model: "Honda", color: "white", year: "2010", country: "UK"}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

The function declarations are hoisted similar to any variables. So the placement for `Vehicle` function declaration doesn't make any difference.

</p>
</details>

---

#### 2. What is the output of below code?
```js
function foo() {
    let x = y = 0;
    x++;
    y++;
    return x;
}

console.log(foo(), typeof x, typeof y);
```

- 1: 1, undefined and undefined
- 2: ReferenceError: X is not defined
- 3: 1, undefined and number
- 4: 1, number and number

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

Of course the return value of `foo()` is 1 due to increment operator. But the statement `let x = y = 0` declares a local variable x. Whereas y declared as a global variable accidentally. This statement is equivalent to,
```js
 let x;
 window.y = 0;
 x = window.y;
```
Since the block scoped variable x is undefined outside of the function, the type will be undefined too. Whereas the global variable `y` is available outside the function, the value is 0 and type is number.
</p>
</details>

---

#### 3. What is the output of below code?
```js
function main(){
  console.log('A');
  setTimeout(
    function print(){ console.log('B'); }
  ,0);
	console.log('C');
}
main();
```

- 1: A, B and C
- 2: B, A and C
- 3: A and C
- 4: A, C and B

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4
The statements order is based on event loop mechanism. The order of statements follows the below order,

1. At first, the main function is pushed to the stack.
2. Then the browser pushes the fist statement of main function( i.e, A's console.log) to the stack, executed and popped out immediately.
3. But `setTimeout` statement moved to Browser API to apply the delay for callback.
4. In the meantime, C's console.log added to stack, executed and popped out.
5. The callback of `setTimetout` moved from Browser API to message queue.
6. The `main` function popped out from stack because there are no statements to execute
7. The callback moved from message queue to the stack since the stack is empty.
8. The console.log for B is added to the stack and display on the console.

</p>
</details>

---

#### 4. What is the output of below equality check?
```js
console.log(0.1 + 0.2 === 0.3);
```

- 1: false
- 2: true


<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1
This is due to float point math problem. Since the floating point numbers are encoded in binary format, the addition operations on them leads to rounding errors. Hence, the comparison of floating point doesn't give expected results.
You can find more details about the explanation here https://0.30000000000000004.com/

</p>
</details>

---

#### 5. What is the output of below code?
```js
var y = 1;
  if (function f(){}) {
    y += typeof f;
  }
  console.log(y);
```

- 1: 1function
- 2: 1object
- 3: ReferenceError
- 4: 1undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4
The main points in the above code snippets are,
1. You can see function expression instead function declaration inside if statement. So it always returns true.
2. Since it is not declared(or assigned) anywhere, f is undefined and typeof f is undefined too.

In other words, it is same as
```js
var y = 1;
  if ('foo') {
    y += typeof f;
  }
  console.log(y);
```
**Note:** It returns 1object for MS Edge browser
</p>
</details>

---

#### 6. What is the output of below code?
```js
function foo() {
  return
  {
    message: "Hello World"
  };
}
console.log(foo());
```

- 1: Hello World
- 2: Object {message: "Hello World"}
- 3: Undefined
- 4: SyntaxError

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3
This is a semicolon issue. Normally semicolons are optional in JavaScript. So if there are any statements(in this case, return) missing semicolon, it is automatically inserted immediately. Hence, the function returned as undefined.

Whereas if the opening curly brace is along with return keyword then function going to be returned as expected.
```js
function foo() {
  return {
    message: "Hello World"
  };
}
console.log(foo()); // {message: "Hello World"}
```
</p>
</details>

---

#### 7. What is the output of below code?
```js
var myChars = ['a', 'b', 'c', 'd']
delete myChars[0];
console.log(myChars);
console.log(myChars[0]);
console.log(myChars.length);
```

- 1: [empty, 'b', 'c', 'd'], empty, 3
- 2: [null, 'b', 'c', 'd'], empty, 3
- 3: [empty, 'b', 'c', 'd'], undefined, 4
- 4: [null, 'b', 'c', 'd'], undefined, 4

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3
The `delete` operator will delete the object property but it will not reindex the array or change its length. So the number or elements or length of the array won't be changed.
If you try to print myChars then you can observe that it doesn't set undefined value, rather the property is removed from the array. The newer versions of Chrome use `empty` instead of `undefined` to make the difference a bit clearer.
</p>
</details>

---

#### 8. What is the output of below code in latest Chrome?
```js
var array1 = new Array(3);
console.log(array1);

var array2 = [];
array2[2] = 100;
console.log(array2);

var array3 = [,,,];
console.log(array3);
```

- 1: [undefined × 3], [undefined × 2, 100], [undefined × 3]
- 2: [empty × 3], [empty × 2, 100], [empty × 3]
- 3: [null × 3], [null × 2, 100], [null × 3]
- 4: [], [100], []

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2
The latest chrome versions displays `sparse array`(they filled with holes) using this empty x n notation. Whereas the older versions has undefined x n notation.
**Note:** The latest version of FF displays `n empty slots` notation.
</p>
</details>

---

#### 9. What is the output of below code?
```js
const obj = {
  prop1: function() { return 0 },
  prop2() { return 1 },
  ['prop' + 3]() { return 2 }
}

console.log(obj.prop1());
console.log(obj.prop2());
console.log(obj.prop3());
```

- 1: 0, 1, 2
- 2: 0, { return 1 }, 2
- 3: 0, { return 1 }, { return 2 }
- 4: 0, 1, undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1
ES6 provides method definitions and property shorthands for objects. So both prop2 and prop3 treated as regular function values.
</p>
</details>

---

#### 10. What is the output of below code?
```js
console.log(1 < 2 < 3);
console.log(3 > 2 > 1);
```

- 1: true, true
- 2: true, false
- 3: SyntaxError, SyntaxError,
- 4: false, false

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2
The important point is that if the statement contains same operators(e.g, < or >) then it be evaluated from left to right.
The first statement follows the below order,
1. console.log(1 < 2 < 3);
2. console.log(true < 3);
3. console.log(1 < 3); // True converted as `1` during comparision
4. True

Whereas the second statement follows the below order,
1. console.log(3 > 2 > 1);
2. console.log(true > 1);
3. console.log(1 > 1); // False converted as `0` during comparision
4. False
</p>
</details>

---

#### 11. What is the output of below code in non-strict mode?
```js
const printNumbers = (first, second, first) => {
  console.log(first, second, first);
}
printNumbers(1, 2, 3);

const printNumbersArrow = (first, second, first) => {
  console.log(first, second, first);
}
printNumbersArrow(1, 2, 3);
```

- 1: 1, 2, 3
- 2: 3, 2, 3
- 3: SyntaxError: Duplicate parameter name not allowed in this context
- 4: 1, 2, 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2
In non-strict mode, the regular JavaScript functions allow duplicate named parameters. The above code snippet has duplicate parameters on 1st and 3rd parameters.
The value of first parameter mapped to the third argument which is passed to the function. Hence, the 3rd argument overrides the first parameter.

**Note:** In strict mode, duplicate parameters will throw a Syntax Error.
</p>
</details>

---

#### 12. What is the output of below code?
```js
const printNumbersArrow = (first, second, first) => {
  console.log(first, second, first);
}
printNumbersArrow(1, 2, 3);
```

- 1: 1, 2, 3
- 2: 3, 2, 3
- 3: SyntaxError: Duplicate parameter name not allowed in this context
- 4: 1, 2, 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3
Unlike regular functions, the arrow functions doesn't not allow duplicate parameters in either strict or non-strict mode. So you can see `SyntaxError` in the console.
</p>
</details>

---

#### 13. What is the output of below code?
```js
const arrowFunc = () => arguments.length;
console.log(arrowFunc(1, 2, 3));
```

- 1: ReferenceError: arguments is not defined
- 2: 3
- 3: undefined
- 4: null

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1
Arrow functions do not have an `arguments, super, this, or new.target` bindings. So any reference to `arguments` variable tries to resolve to a binding in a lexically enclosing environment. In this case, the arguments variable is not defined outside of the arrow function. Hence, you will receive reference error.

Where as the normal function provides the number of arguments passed to the function
```js
const func = function () {
                    return arguments.length;
                    }
console.log(func(1, 2, 3));
```
But If you still want to use an arrow function then rest operator on arguments provides the expected arguments
```js
const arrowFunc = (...args) => args.length;
console.log(arrowFunc(1, 2, 3));
```
</p>
</details>

---

#### 14. What is the output of below code?
```js
console.log( String.prototype.trimLeft.name === 'trimLeft' );
console.log( String.prototype.trimLeft.name === 'trimStart' );
```

- 1: True, False
- 2: False, True

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2
In order to be consistent with functions like `String.prototype.padStart`, the standard method name for trimming the whitespaces is considered as `trimStart`. Due to web web compatibility reasons, the old method name 'trimLeft' still act as a alias for 'trimStart'. Hence, the prototype for 'trimLeft' is always 'trimStart'
</p>
</details>

---

#### 15. What is the output of below code?
```js
console.log(Math.max());
```

- 1: undefined
- 2: Infinity
- 3: 0
- 4: -Infinity

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4
-Infinity is the initial comparant because almost every other value is bigger. So when no arguments are provided, -Infinity is going to returned.
**Note:** Zero number of arguments is a valid case.
</p>
</details>

---

#### 16. What is the output of below code?
```js
console.log(10 === [10]);
console.log(10 === [[[[[[[10]]]]]]]);
```

- 1: True, True
- 2: True, False
- 3: False, False
- 4: False, True

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1
As per the comparison algorithm in the ECMAScript specification(ECMA-262), the above expression converted into JS as below
```js
10 === Number([10].valueOf().toString()) // 10
```
So it doesn't matter about number brackets([]) around the number, it always converted to a number in the expression.
</p>
</details>

---

#### 17. What is the output of below code?
```js
console.log(10 + '10');
console.log(10 - '10');
```

- 1: 20, 0
- 2: 1010, 0
- 3: 1010, 10-10
- 4: NaN, NaN

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2
The concatenation operator(+) is applicable for both number and string types. So if any operand is string type then both operands concatenated as strings. Whereas substract(-) operator tries to convert the operands as number type.
</p>
</details>

---

#### 18. What is the output of below code?
```js
console.log([0] === false);
if([0]) {
console.log("I'm True");
} else {
console.log("I'm False");
}

```

- 1: True, I'm True
- 2: True, I'm False
- 3: False, I'm True
- 4: False, I'm False

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1
In comparision operators, the expression `[0]` converted to Number([0].valueOf().toString()) which is resolved to false. Whereas `[0]` just become a truthy value without any conversion because there is no comparision operator.
</p>
</details>

#### 19. What is the output of below code?
```js
console.log([1, 2] + [3, 4]);
```

- 1: [1,2,3,4]
- 2: [1,2][3,4]
- 3: SyntaxError
- 4: 1,23,4

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4
The + operator is not meant or defined for arrays. So it converts arrays into strings and concatenates them.
</p>
</details>

---

#### 20. What is the output of below code?
```js
const numbers = new Set([1, 1, 2, 3, 4]);
console.log(numbers);

const browser = new Set('Firefox);
console.log(browser);
```

- 1: {1, 2, 3, 4}, {"F", "i", "r", "e", "f", "o", "x"}
- 2: {1, 2, 3, 4}, {"F", "i", "r", "e", "o", "x"}
- 3: [1, 2, 3, 4], ["F", "i", "r", "e", "o", "x"]
- 4: {1, 1, 2, 3, 4}, {"F", "i", "r", "e", "f", "o", "x"}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1
Since `Set` object is a collection of unique values, it won't allow duplicate values in the collection. At the same time, it is case sensitive data structure.
</p>
</details>

---

#### 21. What is the output of below code?
```js
console.log(NaN === NaN);
```

- 1: True
- 2: False

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2
JavaScript follows IEEE 754 spec standards. As per this spec, NaNs are never equal for floating-point numbers.
</p>
</details>

---

#### 22. What is the output of below code?
```js
let numbers = [1, 2, 3, 4, NaN];
console.log(numbers.indexOf(NaN));
```

- 1: 4
- 2: NaN
- 3: SyntaxError
- 4: -1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4
The `indexOf` uses strict equality operator(===) internally and `NaN === NaN` evaluates to false. Since indexOf won't be able to find NaN inside an array, it returns -1 always.
But you can use `Array.prototype.findIndex` method to find out the index of NaN in an array or You can use `Array.prototype.includes` to check if NaN is present in an array or not.
```js
let numbers = [1, 2, 3, 4, NaN];
console.log(numbers.findIndex(Number.isNaN)); // 4

console.log(numbers.includes(Number.isNaN)); // true
```
</p>
</details>

---

#### 23. What is the output of below code?
```js
let [a, ...b,] = [1, 2, 3, 4, 5];
console.log(a, b);
```

- 1: 1, [2, 3, 4, 5]
- 2: 1, {2, 3, 4, 5}
- 3: SyntaxError
- 4: 1, [2, 3, 4]

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3
When using rest parameters, trailing commas are not allowed and will throw a SyntaxError.
If you remove the trailing comma then it displays 1st answer
```js
let [a, ...b,] = [1, 2, 3, 4, 5];
console.log(a, b); // 1, [2, 3, 4, 5]
```
</p>
</details>

---

#### 25. What is the output of below code?
```js
async function func() {
   return 10;
}
console.log(func());
```

- 1: Promise {<resolved>: 10}
- 2: 10
- 3: SyntaxError
- 4: Promise {<rejected>: 10}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1
Async functions always return a promise. But even if the return value of an async function is not explicitly a promise, it will be implicitly wrapped in a promise. The above async function is equivalent to below expression,
```js
function func() {
   return Promise.resolve(10)
}
```
</p>
</details>

---

#### 26. What is the output of below code?
```js
async function func() {
   await 10;
}
console.log(func());
```

- 1: Promise {<resolved>: 10}
- 2: 10
- 3: SyntaxError
- 4: Promise {<resolved>: undefined}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4
The await expression returns value 10 with promise resolution and the code after each await expression can be treated of as existing in a `.then` callback. In this case, there is no return expression at the end of the function. Hence, the default return value of `undefined` is returned as the resolution of the promise.  The above async function is equivalent to below expression,
```js
function func() {
   return Promise.resolve(10).then(() => undefined)
}
```
</p>
</details>

---

#### 27. What is the output of below code?
```js
function delay() {
  return new Promise(resolve => setTimeout(resolve, 2000));
}

async function delayedLog(item) {
  await delay();
  console.log(item);
}

async function processArray(array) {
  array.forEach(item => {
    await delayedLog(item);
  })
}

processArray([1, 2, 3, 4]);
```

- 1: SyntaxError
- 2: 1, 2, 3, 4
- 3: 4, 4, 4, 4
- 4: 4, 3, 2, 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1
Even though “processArray” is an async function, the anonymous function that we use for `forEach` is synchronous. If you use await inside synchronous function then it throws a syntax error.
</p>

</details>

---

#### 28. What is the output of below code?
```js
function delay() {
  return new Promise(resolve => setTimeout(resolve, 2000));
}

async function delayedLog(item) {
  await delay();
  console.log(item);
}

async function process(array) {
  array.forEach(async (item) => {
    await delayedLog(i);
  });
  console.log('Process completed!');
}
process([1, 2, 3, 5]);
```

- 1: 1 2 3 5 and Process completed!
- 2: 5 5 5 5 and Process completed!
- 3: Process completed! and 5 5 5 5
- 4: Process completed! and 1 2 3 5

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4
The forEach method will not wait until all items are finished but it just run the tasks and go next. Hence, the last statement is displayed first followed by sequence of promise resolutions.

But you control the array sequence using for..of loop,

```js
async function processArray(array) {
  for (const item of array) {
    await delayedLog(item);
  }
  console.log('Process completed!');
}
```
</p>
</details>

---

#### 29. What is the output of below code?
```js
var set = new Set();
set.add("+0").add("-0").add(NaN).add(undefined).add(NaN);;
console.log(set);
```

- 1: Set(4) {"+0", "-0", NaN, undefined}
- 2: Set(3) {"+0", NaN, undefined}
- 3: Set(5) {"+0", "-0", NaN, undefined, NaN}
- 4: Set(4) {"+0", NaN, undefined, NaN}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1
Set has few exceptions from equality check,

1. All NaN values are equal
2. Both +0 and -0 considered as different values
</p>
</details>

---

#### 30. What is the output of below code?
```js
const sym1 = Symbol('one');
const sym2 = Symbol('one');

const sym3 = Symbol.for('two');
const sym4 = Symbol.for('two');

cnsooe.log(sym1 === sym2, sym3 === sym4);
```

- 1: true, true
- 2: true, false
- 3: false, true
- 4: false, false

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3
Symbol follows below conventions,

1. Every symbol value returned from Symbol() is unique irrespective of the optional string.
2. `Symbol.for()` function creates a symbol in a global symbol registry list. But it doesn't  necessarily create a new symbol on every call, it checks first if a symbol with the given key is already present in the registry and returns the symbol if it is found. Otherwise a new symbol created in the registry.

**Note:** The symbol description is just useful for debugging purpose.
</p>

</details>

---

#### 31. What is the output of below code?
```js
const sym1 = new Symbol('one');
cnsooe.log(sym1);
```

- 1: SyntaxError
- 2: one
- 3: Symbol('one')
- 4: Symbol

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1
`Symbol` is a just a standard function and not an object constructor(unlike other primitives new Boolean, new String and new Number). So if you try to call it with the new operator will result in a TypeError
</p>

</details>

---

#### 32. What is the output of below code?
```js
let myNumber = 100;
let myString = '100';

if (!typeof myNumber === "string") {
	console.log("It is not a string!");
} else {
    console.log("It is a string!");
}

if (!typeof myString === "number"){
	console.log("It is not a number!")
} else {
    console.log("It is a number!");
}
```

- 1: SyntaxError
- 2: It is not a string!, It is not a number!
- 3: It is a not a string!, It is a number!
- 4: It is a string!, It is a number!

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4
The return value of `typeof myNumber (OR) typeof myString` is always the truthy value (either "number" or "string"). Since ! operator converts the value to a boolean value, the value of both `!typeof myNumber or !typeof myString` is always false. Hence the if condition fails and control goes to else block.
</p>

</details>

---

#### 33. What is the output of below code?
```js
console.log(JSON.stringify({ myArray: ['one', undefined, function(){}, Symbol('')] }));
console.log(JSON.stringify({ [Symbol.for('one')]: 'one' }, [Symbol.for('one')]));
```

- 1: {"myArray":['one', undefined, {}, Symbol]}, {}
- 2: {"myArray":['one', null,null,null]}, {}
- 3: {"myArray":['one', null,null,null]}, "{ [Symbol.for('one')]: 'one' }, [Symbol.for('one')]"
- 4: {"myArray":['one', undefined, function(){}, Symbol('')]}, {}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2
The symbols has below constraints,

1. The undefined, Functions, and Symbols are not valid JSON values. So those values are are either omitted (in an object) or changed to null (in an array). Hence, it returns null values for the value array.
2. All Symbol-keyed properties will be completely ignored. Hence it returns empty object({}).
</p>

</details>

---


#### 34. What is the output of below code?
```js
class A {
  constructor() {
    console.log(new.target.name)
  }
}

class B extends A { constructor() { super() } }

new A();
new B();
```

- 1: A, A
- 2: A, B


<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2
Using constructors, `new.target` refers to the constructor (points to the class definition of class which is initialized) that was directly invoked by new. This is also applies to the case if the constructor is in a parent class and was delegated from a child constructor.
</p>

</details>

---

#### 35. What is the output of below code?
```js
const [x, ...y,] = [1, 2, 3, 4];
console.log(x, y);
```

- 1: 1, [2, 3, 4]
- 2: 1, [2, 3]
- 3: 1, [2]
- 4: SyntaxError

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4
It throws a syntax error because rest element should not have a trailing comma. You should always consider using rest operator as the last element.
</p>

</details>

---

#### 36. What is the output of below code?
```js
const {a: x = 10, b: y = 20} = {a: 30};

console.log(x);
console.log(y);
```

- 1: 30, 20
- 2: 10, 20
- 3: 10, undefined
- 4: 30, undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1
The object property follows below rules,
1. The object properties can be retrieved and assigned to a variable with a different name
2. The property assigned a default value when the retrieved value is `undefined`
</p>

</details>

---

#### 37. What is the output of below code?
```js
function area({length = 10, width = 20}) {
  console.log(length*width);
}

area();
```

- 1: 200
- 2: Error
- 3: undefined
- 4: 0

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2
If you leave out the right-hand side assignment for the destructuring object, the function will look for at least one argument to be supplied when invoked. Otherwise you will receive an error `Error: Cannot read property 'length' of undefined` as mentioned above.

You can avoid the error with either of the below changes,
1. **Pass atleast an empty object:**

```js
function area({length = 10, width = 20}) {
  console.log(length*width);
}

area({});
```

2. **Assign default empty object:**

```js
function area({length = 10, width = 20} = {}) {
  console.log(length*width);
}

area();
```
</p>

</details>

---

#### 38. What is the output of below code?
```js
const props = [
  { id: 1, name: 'John'},
  { id: 2, name: 'Jack'},
  { id: 3, name: 'Tom'}
];

const [,, { name }] = props;
console.log(name);
```

- 1: Tom
- 2: Error
- 3: undefined
- 4: John

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1
It is possible to combine Array and Object destructuring. In this case, third element in the array props accessed first followed by name property in the object.
</p>

</details>

---

#### 39. What is the output of below code?

```js
function checkType(num = 1) {
  console.log(typeof num);
}

checkType();
checkType(undefined);
checkType('');
checkType(null);
```

- 1: number, undefined, string, object
- 2: undefined, undefined, string, object
- 3: number, number, string, object
- 4: number, number, number, number

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3
If the function argument is set implicitly(not passing argument) or explicitly to undefined, the value of the argument is the default parameter. Whereas for other falsy values('' or null), the value of the argument is passed parameter.

Hence, the result of function calls categorized as below,

1. The first two function calls logs number type since the type of default value is number
2. The type of '' and null values are string and object type respectively.

</p>

</details>

---

#### 40. What is the output of below code?

```js
function add(item, items = []) {
  items.push(item);
  return items;
}

console.log(add('Orange'));
console.log(add('Apple'));
```

- 1: ['Orange'], ['Orange', 'Apple']
- 2: ['Orange'], ['Apple']


<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2
Since the default argument is evaluated at call time, a new object is created each time the function is called. So in this case, the new array is created and element pushed to the default empty array.

</p>

</details>

---

#### 41. What is the output of below code?

```js
function greet(greeting, name, message = greeting + ' ' + name) {
  console.log([name, greeting, message]);
}

greet('Hello', 'John');
greet('Hello', 'John', 'Good morning!');
```

- 1: SyntaxError
- 2: ['Hello', 'John', 'Hello John'], ['Hello', 'John', 'Good morning!']


<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2
Since parameters defined earlier are available to later default parameters, this code snippet doesn't throw any error.
</p>

</details>

---

#### 42. What is the output of below code?

```js
function outer(f = inner()) {
  function inner() { return 'Inner' }
}
outer();
```

- 1: ReferenceError
- 2: Inner


<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1
The functions and variables declared in the function body cannot be referred from default value parameter initializers. If you still try to access, it throws a run-time ReferenceError(i.e, `inner` is not defined).
</p>

</details>

---
