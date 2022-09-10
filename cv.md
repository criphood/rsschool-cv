# Artyom Volodin
## Frontend Developer
***
## Contacts:
* **Phone:** +7(977)178-1430;
* **E-mail:** criphood4life@gmail.com;
* [Telegram] (https://t.me/criphood);
* [LinkedIn] (https://www.linkedin.com/in/criphood2304);
***

## Summary:
Two years ago, I graduated from the university and got a job in a departmental organization where I work as a communications engineer.  
Over time I understood that this work doesn't bring me pleasure and I began to look for an occupation to my liking. I have been fascinated with programming since school and I decided to try my hand at front-end development.  
By the current moment I already have several completed projects. I continue my education and don't intend to stop there.
***

## Skills:
* HTML5, CSS3 (SCSS/SASS);
* JavaScript(ES6+);
* ReactJS;
* Git, GitHub;
* Webpack, Gulp;
* npm.
***

## Code Example:
One of the hardests tasks from Stage0: "You have to implement a base converter, which converts positive integers between arbitrary bases / alphabets".
    function convert(input, source, target) {
        const reverseInput = input.split('').reverse().join('');
        let decimal = 0;

        for (let i = 0; i < reverseInput.length; i++) {
            decimal += source.indexOf(reverseInput[i]) * Math.pow(source.   length, i);
        }

        let s = [];

        if (decimal == 0) s.push(decimal);

        while (decimal >= 1) {
            s.push(Math.floor(decimal % target.length));
            decimal /= target.length;
        }

        for (let i = 0; i < s.length; i++) {
            if (target[s[i]].charCodeAt() <= 57) {
                s[i] = String.fromCharCode(s[i] + 48);
            } else {
                s[i] = target[s[i]];
            }
        }

        return s.reverse().join('');
    }

## Education:
* **University:** Saint-Petersburg State University of Telecommunication - Specislist Degree (2020).
* **Courses:** RS School Stage0.
   ![Certificate](/img/certificate.jpg)
***

## Languages:
* **Russian:** Native;
* **English:** Intemediate(B1).
