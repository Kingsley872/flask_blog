---
1. pip install flask 2. pip install flask-wtf
---

# Flask Project

1. pip install flask
2. pip install flask-wtf
3. pip install email_validator
4. pip install flask-sqlalchemy

--------------------------------------------------------------------------------

# command line

1. python3 flaskblog.py or flask run 2.

# command line for db

1. python3
2. from flaskblog import db
3. db.create_all()
4. user_1 = User(username='A', email='A@email.com', password='password')
5. db.session.add(user_1)
6. User.query.all()
7. User.query.first()
8. User.query.filter_by(username='A').all()
9. user = User.query.filter_by(username='A').first()
10. post_1 = Post(title='Blog1', context='First Post Content!', user_id=user.id)
11. post_2 = Post(title='Blog2', content='Second Post Content!', user_id=user.id)
12. db.session.add(post_1)
13. db.session.add(post_2)
14. db.session.commit()
15. user.posts
16. for post in user.posts print(post.title)

--------------------------------------------------------------------------------

# Others

1. get random string token

  1. python3
  2. import secrets
  3. secrets.token_hex(16)

--------------------------------------------------------------------------------

# Reference

Corey Schafer Python Flask
