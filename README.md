# Tumblr Fake User Dataset

## Description
This dataset contains Tumblr user information with posts information. More data would be updated in the future.

## Dataset Structure
There are two files, one is for all user information, another is for posts information

## Columns/Features
Features for user dataset includes:

- user_name: unique user login name
- name: customized user name
- avatar: user profile avatar download link
- total_posts: number of posts user made by the time of collection
- description: self description
- allow_question: allow non-follower to ask question
- allow_question_anon: allow non-follower to ask question anonymously
- fake: binary 0-1 label. 1 stands for a fake user

Features for posts dataset includes:
- blog_name:  unique user login name
- id: post unique id
- date: posted date
- type: type of post
- is_blocks_post_format: whether it is a block post
- tags: tags of post
- note_count: number of notes by the time of collection
- summary: summary of the post
- slug: user given slug
- original_author: original author for reblog posts
- interactability_reblog: whether can be reblogged
- interactability_blaze: whether can be interacted
- like_count: number of likel received by the time of collection
- reblog_count: number of reblogs by the time of collection
- posted_count: number of posted received by the time of collection
- likelist: users who liked the post by the time of collection
- rebloglist: users who reblogged the post by the time of collection
- postlist: users who interacted with the post by the time of collection


<!-- ## Data Collection Method
Explain how the data was collected. This section can include information about:

- The methodology used for data collection
- Time frame of data collection
- Any biases or limitations in the data collection process -->

## Usage
Run collector.ipynb for collecting data. The Tumblr login info can be changed in collector.py

## Licensing
Copyright 2013 Tumblr, Inc.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations.

## Acknowledgements
This dataset collection largely used pytumblr