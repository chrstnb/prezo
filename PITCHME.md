# Computer Science
### my experiences with it & how you can give it a try

---
## A little about me
- Undergrad computer engineering student at the university of washington in seattle

- Interned at google this past summer

- Started programming about a year ago (though I wish I'd started sooner!)

---
## Why you should try programming
- **There are tons of applications in every field**; you can use it in areas you're passionate about even if they're not not directly in the realm of technology

- If you like math, there are a lot of things you'll love in Computer Science; it's built on math!

- If you don't *love* math, that's okay too!
---

<canvas id="myChart" width="400" height="400"></canvas>
<script>
var ctx = document.getElementById("myChart").getContext('2d');
var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
        labels: ["Red", "Blue", "Yellow", "Green", "Purple", "Orange"],
        datasets: [{
            label: '# of Votes',
            data: [12, 19, 3, 5, 2, 3],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255,99,132,1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero:true
                }
            }]
        }
    }
});
</script>
![image of why](vega.png)

---
## How you can try programming
### At school
- Consider taking computer science and web programming classes

- Try robotics!

- Join the Cyber Patriots club!

- Try to integrate some programming into your coursework, like using Processing (more on the next slide) in an art class or making a cool data visualization for a presentation

## Things you can try on your own
- Anything from [Beyond CS First](https://www.cs-first.com/en/beyond-cs-first)

- Courses on [Lynda.com](www.lynda.com)
  * Use your Mid-Continent Public Library card for free access! 😉

- Make a personal site on [Github](github.com)
  * The [JMcglone tutorial](http://jmcglone.com/guides/github-pages/) is especially good
