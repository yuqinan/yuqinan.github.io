---
layout: default
---

<div class="home">
  <section class="main-content">
    <div class="container">
      <h1 class="title is-1 mt-6 mb-4">Qinan Yu <span style="font-size: 0.4em; font-family: '仿宋', FangSong, STFangsong, serif;">喻启楠</span></h1>
      
      <!-- Desktop/tablet layout with image -->
      <div class="profile-container">
        <div class="columns">
          <div class="column is-two-thirds">
            <div class="bio-content mb-5">
              <p class="mb-3">Hi! I am qinan, a first-year CS Ph.D. student at Stanford. 
               Currently, I am rotating with <a href="https://stanford.edu/~cgpotts/" target="_blank" rel="noopener noreferrer">Chris Potts</a> and <a href="https://guestrin.su.domains/" target="_blank" rel="noopener noreferrer">Carlos Guestrin</a>. My Ph.D. is generously supported by <a href="https://vpge.stanford.edu/fellowships-funding/sgf" target="_blank" rel="noopener noreferrer">Stanford Graduate Fellowship</a></p>.

              <p class="mb-5">My research focuses on Natural Language Processing, specifically in interpretability and trustworthiness of language models. 
              I'm interested in understanding how language models work internally and improving their capabilities and reliability.</p>
              
              <p class="mb-3">Before Stanford, I received a concurrent B.S. in Math-CS and M.A. in CS from Brown where I was fortunate to be advised by <a href="https://cs.brown.edu/people/epavlick/" target="_blank" rel="noopener noreferrer">Ellie Pavlick</a>.</p>
          
              
              <div class="links-section">
                <a href="mailto:qinanyu@stanford.edu" class="simple-link">email</a>
                <a href="https://github.com/yuqinan" target="_blank" rel="noopener noreferrer" class="simple-link">github</a>
                <a href="https://scholar.google.com/citations?user=ZzQoxXcAAAAJ&hl=en" target="_blank" rel="noopener noreferrer" class="simple-link">google scholar</a>
                <a href="https://x.com/qinan_yu" target="_blank" rel="noopener noreferrer" class="simple-link">twitter</a>
              </div>
            </div>
          </div>
          
          <div class="column is-one-third">
            <figure class="image">
              <img class="profile-pic" src="assets/images/qinan.jpg" alt="Qinan Yu profile photo">
            </figure>
          </div>
        </div>
      </div>
      
      <!-- Mobile-only content (hidden on desktop) -->
      <div class="mobile-bio-content" style="display: none;">
        <div class="bio-content mb-5">
          <p class="mb-3">Hi! I am qinan, a first-year CS Ph.D. student at Stanford. 
           Currently, I am rotating with <a href="https://stanford.edu/~cgpotts/" target="_blank" rel="noopener noreferrer">Chris Potts</a> and <a href="https://guestrin.su.domains/" target="_blank" rel="noopener noreferrer">Carlos Guestrin</a>. My Ph.D. is generously supported by <a href="https://vpge.stanford.edu/fellowships-funding/sgf" target="_blank" rel="noopener noreferrer">Stanford Graduate Fellowship</a></p>

          <p class="mb-5">My research focuses on Natural Language Processing, specifically in interpretability and trustworthiness of language models. 
          I'm interested in understanding how language models work internally and improving their capabilities and reliability.</p>
          
          <p class="mb-3">Before Stanford, I received a concurrent B.S. in Math-CS and M.A. in CS from Brown where I was fortunate to be advised by <a href="https://cs.brown.edu/people/epavlick/" target="_blank" rel="noopener noreferrer">Ellie Pavlick</a>.</p>
          
          <div class="links-section">
            <a href="mailto:qinanyu@stanford.edu" class="simple-link">email</a>
            <a href="https://github.com/yuqinan" target="_blank" rel="noopener noreferrer" class="simple-link">github</a>
            <a href="https://scholar.google.com/citations?user=ZzQoxXcAAAAJ&hl=en" target="_blank" rel="noopener noreferrer" class="simple-link">google scholar</a>
            <a href="https://x.com/qinan_yu" target="_blank" rel="noopener noreferrer" class="simple-link">twitter</a>
          </div>
        </div>
      </div>
      
      <h2 class="title is-3 mt-6 mb-4">News</h2>
      <div class="content news-section">
        <ul class="news-list">
          <li class="news-item mb-4">
            <div class="news-date"><strong>May 2025</strong></div>
            <div class="news-content">Our paper <a href="https://arxiv.org/abs/2505.20809" class="paper-link" target="_blank" rel="noopener noreferrer">"Improved Representation Steering for Language Models"</a> is now available on arXiv.</div>
          </li>
          <li class="news-item mb-4">
            <div class="news-date"><strong>Jan 2025</strong></div>
            <div class="news-content">Our paper <a href="https://arxiv.org/abs/2410.09223" class="paper-link" target="_blank" rel="noopener noreferrer">"The Same But Different: Structural Similarities and Differences in Multilingual Language Modeling"</a> is accepted into ICLR 2025.</div>
          </li>
          <li class="news-item mb-4">
            <div class="news-date"><strong>Sep 2024</strong></div>
            <div class="news-content">Start my Ph.D. at Stanford.</div>
          </li>
        </ul>
        <p class="mt-5">See my <a href="{{ '/publications/' | relative_url }}" class="is-link">publications page</a> for a complete list of papers.</p>
      </div>
    </div>
  </section>
</div>

<style>
  .simple-link {
    display: inline-block;
    margin-right: 1rem;
    padding: 0.3rem 0.7rem;
    font-weight: 500;
    color: var(--stanford-cardinal);
    border: 2px solid var(--stanford-cardinal);
    background-color: transparent;
    text-decoration: none;
    transition: all 0.2s ease;
  }
  
  .simple-link:hover {
    background-color: var(--stanford-cardinal);
    color: white;
  }
  
  .news-list {
    list-style-type: none !important;
    margin-left: 0 !important;
    padding-left: 0;
  }
  
  .news-item {
    display: flex;
    align-items: flex-start;
  }
  
  .news-date {
    min-width: 120px;
    color: #555;
    padding-right: 1rem;
    flex-shrink: 0;
  }
  
  .news-content {
    flex: 1;
  }
  
  .bio-content {
    line-height: 1.7;
  }
  
  .links-section {
    margin-top: 2rem;
  }
  
  /* Show mobile content only on mobile */
  @media screen and (max-width: 480px) {
    .mobile-bio-content {
      display: block !important;
    }
  }
</style> 