# Query Selector linkedIn

// fulfill user name
document.querySelectorAll('#username')[0].innerText = 'raphael.moita@gmail.com'
// fulfill user password
document.querySelectorAll('#password')[0].value = '***********'
// click on submit button
document.querySelectorAll('button[aria-label="Sign in"]')[0].click()

// get profile name
document.querySelectorAll('.profile-rail-card__actor-link.t-16.t-black.t-bold')[0].innerText
// or
document.querySelectorAll('div[data-control-name="identity_welcome_message"]')[0].innerText
// or
document.querySelector('#ember897 > div:nth-child(2)').innerText
