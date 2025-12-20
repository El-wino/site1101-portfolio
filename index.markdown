---
layout: home
---

<!-- Hero: profile photo + short bio -->
<style>
.profile-hero {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin: 2rem 0;
}
.profile-photo {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid #fff;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}
.profile-bio {
  max-width: 720px;
}
@media (max-width: 600px) {
  .profile-hero { flex-direction: column; text-align: center; }
  .profile-photo { width: 130px; height: 130px; }
}
</style>

<section class="profile-hero">
  <img src="{{ '/assets/images/profilephoto.jpg' | relative_url }}" alt="Profile photo" class="profile-photo" />

  <div class="profile-bio">
    <h1>Hello — I'm Elvin Orujov</h1>
    <p>I'm a first year Computer Science student in ADA university. I enjoy coding and learning.</p>
  </div>
</section>
