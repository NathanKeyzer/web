var hamburger = document.querySelector(".hamburger"),
  closeHamburger = document.querySelector(".mobile-header button"),
  nav = document.querySelector('nav'),
  pageSorting = document.querySelectorAll('.page-sorting p'),
  bookmark = document.querySelectorAll('article .bookmark'),
  profile = document.querySelector('.icon-passenger'),
  heart = document.querySelectorAll('p.pub-date .heart-box')

hamburger.addEventListener("click", function() {
  nav.classList.toggle('open')
})

closeHamburger.addEventListener("click", function() {
  nav.classList.toggle('open')
})

for (var i = 1; i < pageSorting.length; i++) {
  pageSorting[i].addEventListener('click', function() {
    this.classList.toggle('open')
  })
}

for (var i = 0; i < bookmark.length; i++) {
  bookmark[i].addEventListener('click', function() {
    this.classList.toggle('open')

    if ( this.classList.contains('open') ) {
      profile.classList.add( 'dance' )
    }
  })
}

profile.addEventListener('transitionend', function() {
  this.classList.remove('dance')
  this.classList.remove('like')
})

for (var i = 0; i < heart.length; i++) {
  heart[i].addEventListener('click', function() {
    this.classList.toggle('open')

    if ( this.classList.contains('open') ) {
      profile.classList.add( 'like' )
    }
  })
}
