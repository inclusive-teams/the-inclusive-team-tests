# The Inclusive Team Tests

The Inclusive Team Tests are a collection of tests which can be used to roughly determine how inclusive a team is of a particular group. The level of inclusiveness (or disadvantagement) that a particular group might expereince within a certain working environment can be expressed as a score on the test. The concept for these tests was heavily influenced by [The Joel Test](http://www.joelonsoftware.com/articles/fog0000000043.html).


## The Joel Test
Have you heard of [The Joel Test](http://www.joelonsoftware.com/articles/fog0000000043.html)? Go ahead and follow that link and read the article if you haven't. This can wait til you get back. 

In case you haven't read it or don't go read it right now, here is the intro (from the linked article by [Joel Spolsky](http://joelonsoftware.com)):

> I've come up with my own, highly irresponsible, sloppy test to rate the quality of a software team. The great part about it is that it takes about 3 minutes. With all the time you save, you can go to medical school.
>
>
>  
> #### The Joel Test
>
>* Do you use source control?
>* Can you make a build in one step?
>* Do you make daily builds?
>* Do you have a bug database?
>* Do you fix bugs before writing new code?
>* Do you have an up-to-date schedule?
>* Do you have a spec?
>* Do programmers have quiet working conditions?
>* Do you use the best tools money can buy?
>* Do you have testers?
>* Do new candidates write code during their interview?
>* Do you do hallway usability testing?
>
>
>The neat thing about The Joel Test is that it's easy to get a quick yes or no to each question. You don't have to figure out lines-of-code-per-day or average-bugs-per-inflection-point. Give your team 1 point for each "yes" answer. The bummer about The Joel Test is that you really shouldn't use it to make sure that your nuclear power plant software is safe.
>
>A score of 12 is perfect, 11 is tolerable, but 10 or lower and you've got serious problems. The truth is that most software organizations are running with a score of 2 or 3, and they need serious help, because companies like Microsoft run at 12 full-time. 
>
>Of course, these are not the only factors that determine success or failure: in particular, if you have a great software team working on a product that nobody wants, well, people aren't going to want it. And it's possible to imagine a team of "gunslingers" that doesn't do any of this stuff that still manages to produce incredible software that changes the world. But, all else being equal, if you get these 12 things right, you'll have a disciplined team that can consistently deliver.


This is a wonderful concept and the test has become a widely accepted "grassoots" metric for the software industry. A number of companies now advertise their "Joel Test Score" during recruitment and many of the topics that the test covers are discussed on a regular basis (whereas previously they were often ignored). 

The Joel Test has definitely raised the bar of expectations. Although it's an imperfect and sloppy test, it has been effective in improving the overall quality of companies by stating in simple terms the expectations and values that make a great software team. 

## Measuring Inclusiveness and Disadvantagement

The world needs The Joel Test for other topics as well. Specifically -- measuring inclusiveness and disadvantagement. 

**Inclusiveness** means that no group is alienated by the practices and culture of a team. 
**Disadvantagement** means measuring wether or not a team provides a level playing field vs creating an environment that advantages certain groups of people over other people. 

## The Ada Test: Women In Technology 

A concrete use case is always a good starting point. To make it easy, let's pick a group and environment and roll with that. One of the more glaring issues that any developer will be familiar with: women in technology. 

Women are a disadvantaged group in the technology industry. Women don't get hired as often, they don't get equivalent salaries, they get subtly (and sometimes not so subtly) discriminated against and mistreated once they have a job. Sometimes there is no obvious mistreatment but they don't feel welcomed or appreciated compared to others on the team and nebulous matters of "fit" become very problematic. There's a lot of things to talk about here and there are a million reasons why but for now we don't need to discuss those reasons or describe the problem in too much detail. We just want to do a quick and dirty measurement to see if a technology company does not disadvantage women. 

Here's an example test, we'll call it The Ada Test after [Ada Lovelace](http://en.wikipedia.org/wiki/Ada_Lovelace):

### The Ada Test

1. Does the ratio of women to non-women match your local census polls? 
2. Do women's tenures match non-women?
3. Do women's salaries match non-women?
4. Do women write code?
5. Do women make business decisions without approval?
6. Does your company's marketing portray women similarly to non-women?
7. Do office conversations refrain from pointing out differences between women and non-women?
8. Can a woman either challenge or enjoy her traditional gender role without drawing special attention/comments?
9. Are women able to openly discuss problems with how they are treated and are those issues acted upon afterwards?
10. When a woman requests consideration for a uniquely female personal matter, are those requests honored?


As you can see, in this test, one could easily replace "woman" and "women" with any potentially disadvantaged group, like say "homosexuals", "Muslims", "midgets" or "redheads". We could even replace it with general terms like "the concerned group member". By stating a test in general terms it would allow that test to apply to a lot of situations rather than just focusing on a particular demographic in a particular kind of environment.

## Usage

The goal is for no group to be disadvantaged so to address that we start by applying some basic metrics using the test score metaphor. If your company scores 10/10 or even as low as 8/10 on this test, high fives. That's awesome and rare (though it should be the standard). If your company scored 7/10 or less on the above test (for any group, women or otherwise) then there are *serious* problems which should be a red flag to anyone who is a member of a disadvantaged group who is considering working for your company.

Hopefully, folks will come to job interviews armed with this test.

## Project Goals

Create a generalized test which can be applied to any situation. Use this as a basis to create numerous more specific tests which focus on certain groups and environments, each with thier own unique names. This project can collect and maintain these tests and ensure one is available for any scenario. 

