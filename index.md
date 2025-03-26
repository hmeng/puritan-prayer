---
layout: default
title: Home
---

<section class="hero">
  <div class="hero-content">
    <h1>Praying with the Puritans</h1>
    <h2>An Accessible Guide to Prayer from the Puritan Tradition</h2>
    <p>Discover timeless wisdom and practical guidance for a deeper prayer life, inspired by the rich Puritan tradition.</p>
    <div class="cta-buttons">
      <a href="{{ '/chapters/introduction' | relative_url }}" class="btn btn-primary">Start Reading</a>
      <a href="{{ '/about' | relative_url }}" class="btn btn-secondary">Learn More</a>
    </div>
  </div>
</section>

<section class="book-overview">
  <div class="section-container">
    <h2>What You'll Discover</h2>
    <div class="feature-grid">
      <div class="feature-item">
        <h3>The Heart of Prayer</h3>
        <p>Explore the Puritan understanding of prayer as intimate communion with God and learn how to cultivate a genuine heart for prayer.</p>
      </div>
      <div class="feature-item">
        <h3>Practical Wisdom</h3>
        <p>Gain practical insights and techniques for developing an effective prayer life, drawn from the writings of Richard Baxter, Thomas Watson, and other Puritan masters.</p>
      </div>
      <div class="feature-item">
        <h3>Overcoming Obstacles</h3>
        <p>Learn strategies for dealing with common struggles in prayer such as distraction, dryness, and doubt, guided by John Owen and other Puritan teachers.</p>
      </div>
      <div class="feature-item">
        <h3>Scripture-Guided Prayer</h3>
        <p>Discover how to incorporate Scripture into your prayers, following the model of Matthew Henry and other Puritan expositors.</p>
      </div>
    </div>
  </div>
</section>

<section class="chapters-preview">
  <div class="section-container">
    <h2>Book Contents</h2>
    <div class="chapters-list">
      <div class="part">
        <h3>Part 1: The Heart and Foundation of Prayer</h3>
        <ul>
          <li><a href="{{ '/chapters/chapter-1' | relative_url }}">Chapter 1: Recognizing the Necessity of Prayer</a></li>
          <li><a href="{{ '/chapters/chapter-2' | relative_url }}">Chapter 2: Preparing the Heart for Prayer</a></li>
        </ul>
      </div>
      <div class="part">
        <h3>Part 2: Practical Wisdom for Effective Prayer</h3>
        <ul>
          <li><a href="{{ '/chapters/chapter-3' | relative_url }}">Chapter 3: Principles of Effective Prayer</a></li>
          <li><a href="{{ '/chapters/chapter-4' | relative_url }}">Chapter 4: Overcoming Common Barriers to Prayer</a></li>
        </ul>
      </div>
      <div class="part">
        <h3>Part 3: Aligning Prayer with God's Will</h3>
        <ul>
          <li><a href="{{ '/chapters/chapter-5' | relative_url }}">Chapter 5: Discerning and Submitting to God's Will</a></li>
          <li><a href="{{ '/chapters/chapter-6' | relative_url }}">Chapter 6: Biblically Grounded Prayer</a></li>
        </ul>
      </div>
      <div class="part">
        <h3>Part 4: Exploring Biblical Prayer Models</h3>
        <ul>
          <li><a href="{{ '/chapters/chapter-7' | relative_url }}">Chapter 7: Insights from Biblical Prayers</a></li>
          <li><a href="{{ '/chapters/chapter-8' | relative_url }}">Chapter 8: The Psalms as a Prayer Manual</a></li>
        </ul>
      </div>
    </div>
  </div>
</section>

<style>
  /* Home Page Specific Styles */
  .hero {
    padding: 4rem 0;
    text-align: center;
    background-color: var(--light-background);
    border-radius: 8px;
    margin-bottom: 3rem;
  }
  
  .hero-content {
    max-width: 800px;
    margin: 0 auto;
    padding: 0 1.5rem;
  }
  
  .hero h1 {
    font-size: 3rem;
    margin-bottom: 0.5rem;
    color: var(--primary-color);
  }
  
  .hero h2 {
    font-size: 1.5rem;
    font-weight: normal;
    color: var(--light-text);
    margin-bottom: 1.5rem;
  }
  
  .hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
  }
  
  .cta-buttons {
    display: flex;
    justify-content: center;
    gap: 1rem;
  }
  
  .btn {
    display: inline-block;
    padding: 0.8rem 1.5rem;
    border-radius: 4px;
    font-family: 'Open Sans', Helvetica, sans-serif;
    font-weight: 600;
    text-align: center;
    transition: all 0.3s ease;
  }
  
  .btn-primary {
    background-color: var(--primary-color);
    color: white;
  }
  
  .btn-primary:hover {
    background-color: #583a7e;
    color: white;
  }
  
  .btn-secondary {
    background-color: white;
    color: var(--primary-color);
    border: 2px solid var(--primary-color);
  }
  
  .btn-secondary:hover {
    background-color: var(--light-background);
  }
  
  .section-container {
    max-width: 1000px;
    margin: 0 auto;
    padding: 3rem 1.5rem;
  }
  
  .book-overview h2, .chapters-preview h2 {
    text-align: center;
    margin-bottom: 2.5rem;
    font-size: 2.2rem;
  }
  
  .feature-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
  }
  
  .feature-item {
    background-color: var(--light-background);
    border-radius: 8px;
    padding: 1.5rem;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
  }
  
  .feature-item h3 {
    margin-bottom: 1rem;
    color: var(--primary-color);
  }
  
  .chapters-preview {
    background-color: var(--light-background);
    margin-top: 3rem;
  }
  
  .chapters-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
    gap: 2rem;
  }
  
  .part h3 {
    border-bottom: 2px solid var(--primary-color);
    padding-bottom: 0.5rem;
    margin-bottom: 1rem;
  }
  
  .part ul {
    list-style: none;
  }
  
  .part li {
    margin-bottom: 0.8rem;
    padding-left: 1rem;
    position: relative;
  }
  
  .part li:before {
    content: "•";
    position: absolute;
    left: 0;
    color: var(--primary-color);
  }
  
  @media (max-width: 768px) {
    .hero h1 {
      font-size: 2.5rem;
    }
    
    .hero h2 {
      font-size: 1.3rem;
    }
    
    .cta-buttons {
      flex-direction: column;
      gap: 0.8rem;
    }
    
    .chapters-list {
      grid-template-columns: 1fr;
    }
  }
</style> 