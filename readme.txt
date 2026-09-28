
NEXORA CONTACT COMMUNICATION SYSTEM
====================================
Flow:
Website Visitor -> Contact System -> Firebase Firestore -> NEXORA Admin Inbox

1. Firebase Authentication:
   Enable Anonymous sign-in for website visitors.
   Keep Email/Password enabled for the NEXORA admin account.

2. Firestore:
   Deploy firestore.rules from this package.

3. Admin:
   Footer -> Admin -> Login.
   The admin email used by the existing login is:
   admin@nexorainnovators.app

4. Contact:
   Visitors can start a real-time conversation from Contact.
   Conversation messages are stored in:
   contactConversations/{conversationId}/messages

5. Social links:
   WhatsApp Channel:
   https://whatsapp.com/channel/0029VbD7ZgEInlqQB8BaiW22
   YouTube:
   https://www.youtube.com/@NEXORAINNOVATORS

Team members remain code-managed. Project data/images remain cloud-managed as already configured.


IMAGE UPDATE
- Supplied electronics photos from Image.zip and danu.zip are bundled locally under assets/electronics/photos/.
- Matching component records in js/electronics-data.js point to these local images.
- No electronics image is stored in Firebase.
- Communication system remains: Visitor -> Firebase Firestore -> NEXORA Admin Inbox.
- Project cover/gallery uploads remain Firebase Storage-backed from the Admin panel.
