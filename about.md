---
layout: page
title: Σχετικά
permalink: /about/
---

<div class="wrapper">
  <h1 class="title">{{ page.title }}</h1>

  <p>Ο ιστότοπος <strong>Greek-writer</strong> δημιουργήθηκε με σκοπό να παρουσιάσει και να αναδείξει 
  τους σύγχρονους <strong>Έλληνες συγγραφείς</strong> αναγνωρισμένα μέλη της κοινότητας της Ελληνικής
  Εταιρείας Συγγραφέων μέσα από ένα ψηφιακό περιβάλλον ανοιχτής πρόσβασης.</p>

  <p>Η προσπάθεια αυτή εντάσσεται στο πλαίσιο εκπαιδευτικών και ερευνητικών δράσεων του 
  Προγράμματος Μεταπτυχιακών Σπουδών <strong>«Ψηφιακές Εφαρμογές και Καινοτομία»</strong> του 
  <strong>Ιονίου Πανεπιστημίου</strong> και υλοποιήθηκε με χρήση <strong>ανοιχτών δεδομένων (Wikidata)</strong> 
  και της πλατφόρμας <strong>GitHub Pages</strong>.</p>

  <p>Μέσα από τη συλλογή και την οργάνωση πληροφοριών για Έλληνες λογοτέχνες, 
  το έργο επιδιώκει να προωθήσει την <strong>πολιτιστική γνώση</strong>, να ενισχύσει τον <strong>ψηφιακό εγγραμματισμό</strong>
  και να αναδείξει τη <strong>διασύνδεση της τεχνολογίας με τον πολιτισμό</strong>.</p>

  <blockquote>«Η γνώση που μοιράζεται, γίνεται πολιτισμός.»</blockquote>

  <ul class="social-icons">
    <li>
      <a href="https://www.youtube.com/@%CE%95%CF%84%CE%B1%CE%B9%CF%81%CE%B5%CE%AF%CE%B1%CE%A3%CF%85%CE%B3%CE%B3%CF%81%CE%B1%CF%86%CE%AD%CF%89%CE%BD/videos" aria-label="Ακολουθείστε μας στο Youtube" target="_blank" rel="noopener noreferrer">
        <img src="/assets/images/youtube.png" width="24" height="24" alt="YouTube">
      </a>
    </li>
    <li>
      <a href="https://www.facebook.com/HellenicAuthorsSociety" aria-label="Επισκεφτείτε την σελίδα μας στο Facebook" target="_blank" rel="noopener noreferrer">
        <img src="/assets/images/facebook.png" width="24" height="24" alt="Facebook">
      </a>
    </li>
  </ul>
</div>

<style>
.social-icons { 
  list-style: none; 
  padding: 0; 
  display: flex; 
  gap: 12px; 
  margin: 20px 0;
  justify-content: center;
}
.social-icons a { 
  display: inline-flex; 
  width: 44px; 
  height: 44px; 
  align-items: center; 
  justify-content: center; 
  color: #333; 
  text-decoration: none; 
  border-radius: 6px; 
  background-color: #ecf0f1;
  transition: all 0.3s ease;
}
.social-icons a:hover, .social-icons a:focus { 
  background: #3498db; 
  color: white; 
  outline: 2px solid #cce7ff; 
  outline-offset: 3px; 
  transform: scale(1.1);
}
.social-icons img { 
  width: 24px; 
  height: 24px; 
}

body {
  background-color: #2c3e50;
  color: #ecf0f1;
  margin: 0;
  padding: 20px;
  font-family: Arial, sans-serif;
  line-height: 1.6;
}

.wrapper {
  background-color: #34495e;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.3);
  color: #ecf0f1;
  max-width: 800px;
  margin: 0 auto;
}

h1, h2, h3 {
  color: #e74c3c;
  border-bottom: 2px solid #e74c3c;
  padding-bottom: 10px;
}

a {
  color: #3498db;
  text-decoration: none;
  transition: color 0.3s ease;
}

a:hover {
  color: #e74c3c;
  text-decoration: underline;
}

.title {
  color: #e74c3c;
  text-align: center;
}

blockquote {
  border-left: 4px solid #e74c3c;
  padding-left: 20px;
  margin: 20px 0;
  font-style: italic;
  color: #bdc3c7;
  text-align: center;
  font-size: 1.1em;
}
</style>
