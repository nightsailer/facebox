Please visit http://defunkt.github.com/facebox/ or 
open index.html in your favorite browser.

Docs also available as comments in facebox itself:
  http://github.com/defunkt/facebox/blob/master/facebox.js

Need help?  Join our Google Groups mailing list:
  http://groups.google.com/group/facebox/
  
New feature:
 
  facebox_data
  
  This taconite plugin help facebox to works with jquery taconite. Now, any backend
  can return taconite response, and wrap the content into facebox_data will be rendered
  by facebox, and you also have taconite power too!.
  
  Example taconite reponse:

  <taconite>
  <facebox_data>
    <h2 id="note">Hello, I'm taconite page</h2>
  </facebox_data>
  <fadeOut select="#note" />
  <eval>
    alert('cool!');
  </eval>
  </taconite>