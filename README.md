# Planning our application

  1. Answer Questions
    - What are we building?
    - Who are we building it for?
    - What features do we need to have?
  2. User Stories
  3. Model our Data
  4. Think through the pages we need in our app

## Questions

  1. What are we building? 我在做一个写卡片的网站.
  2. Who are we building it for? 我自己, maybe 其他写卡片的人.

  3. What features do we need to have?
    - 卡片
      - CRUD
    - User (Devise)

## User Stories
As a blank, I want to be able to blank, so that blank.

1. 作为一个用户, 我希望能够创建卡片, 用来记录我的笔记或者思考.
2. 作为一个用户, 我希望能修改/删除卡片, 以管理我的卡片.

## Modeling our Data

**Card**
- title:string
- content:text

**User** (Devise)

## Think through the pages we need in our app
- Cards
  - index/show/new/edit
