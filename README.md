# The Recap AI + AI Automation Mastery n8n Workflows

Collection of n8n agents, workflows, and automations created and maintained by **The Recap AI** — Join our free [AI Automation Community](https://www.skool.com/ai-automation-mastery-group) to connect with AI builders learn how to build 

## Agents

### Marketing Team Voice Agent

[marketing_team_agent.json](https://youtu.be/_HOHQqjsy0U) - AI voice agent to replace your marketing team. Uses ElevenLabs and an n8n agent to handle daily marketing tasks such as writing newsletters, generating images, repurposing content, and creating videos.

- [write_newsletter_tool.json](https://youtu.be/_HOHQqjsy0U) - Automates the entire process of generating an AI-focused newsletter. It collects news, filters and selects top stories, writes engaging summaries and sections in a specific style, and formats the content for email delivery. The tool ensures each newsletter is unique, relevant, and ready for distribution, with built-in quality checks and Slack integration for team review.
- [generate_image_tool.json](https://youtu.be/_HOHQqjsy0U) - Generates custom images using OpenAI’s image generation API, following strict brand guidelines for newsletter and marketing content. The tool takes a prompt and context, applies Recap AI’s visual style rules, and posts the resulting image directly to a Slack channel for the marketing team.
- [generate_talking_avatar_tool.json](https://youtu.be/_HOHQqjsy0U) - Creates a talking avatar video from a provided script using the HeyGen API. The tool generates a video with a selected avatar and voice, waits for processing, checks the video status, and shares the final video link in Slack for the team to use in marketing or social content.
- [repurpose_to_short_form_script_tool.json](https://youtu.be/_HOHQqjsy0U) - Converts newsletter or long-form content into engaging short-form video scripts, optimized for platforms like TikTok, Instagram Reels, and YouTube Shorts. Helps the marketing team quickly generate viral-ready video scripts from existing content.
- [repurpose_to_twitter_thread_tool.json](https://youtu.be/_HOHQqjsy0U) - Transforms newsletter content into a compelling, multi-tweet Twitter/X thread. Automatically distills the most important news and insights into a format designed to drive engagement and discussion on social media.
- [email_research_report_tool.json](https://youtu.be/_HOHQqjsy0U) - Sends detailed research reports via email to team members or stakeholders. Converts markdown research content into formatted HTML and delivers it directly to the specified inbox, streamlining the sharing of deep-dive research and analysis.

### Dental Practice Voice Agent

[dental_practice_voice_agent.json](https://www.youtube.com/watch?v=vQ5Z8-f-xw4) - AI-powered voice agent for dental practices that handles appointment scheduling, checks Google Calendar availability, books appointments, and logs patient details to Google Sheets, all via natural language.

## Workflows & Automations

- [ai_scraping_pipeline.json](https://www.youtube.com/watch?v=2uwV4aUyGIg) - Uses Google News, Firecrawl, and rss.app to scrape virtually any piece of web content and transform it into LLM-ready output.
- [twitter_reply_guy_agent.json](https://www.youtube.com/watch?v=Q_b5uPndsLY) - Uses a Mention.com Twitter / X keyword monitoring feed to monitor incoming Twitter posts for certain keywords then uses AI to evaluate and post a reply.
- [firecrawl_email_scraper.json](https://www.youtube.com/watch?v=zasYpLeMV9g) - Uses firecrawl `/map` and `/scrape` endpoints to scrape all email addresses from a given website.
- [write_seo_optimized_listicle_article.json](https://www.youtube.com/watch?v=uDrkgEuEOBA) - Uses Chat GPT Deep Research output to generate an SEO-optimized article and publish to your CMS.
- [ai_news_data_ingestion.json](https://www.youtube.com/watch?v=Nv5_LU0q1IY) - Automatically ingests and processes AI news content from multiple sources (Google News, AI Subreddits, Hacker News, and more sources) using RSS feeds and evaluates content relevance.
- [ai_newsletter_generator.json](https://www.youtube.com/watch?v=Nv5_LU0q1IY) - Generates AI-focused newsletters by selecting top stories, writing engaging content, and formatting with proper markdown structure.
- [firecrawl_scrape_url.json](https://www.youtube.com/watch?v=Nv5_LU0q1IY) - A reusable workflow that uses Firecrawl to extract the main text content and relevant images from any URL, optimized for content processing and LLM prompting.
- [cal_ai_clone_backend.json](https://www.youtube.com/watch?v=4c-kYOiksFg) - Analyzes meal images using AI to estimate calories and nutrition, then returns results as JSON for your app.
- [veo_3_viral_bigfoot_vlog_generator.json](https://www.youtube.com/watch?v=C65c8itWvf4) - Generates a multi-scene, AI-scripted Bigfoot vlog video from a user idea, gets human approval, and creates the final video using VEO 3.
- [short_form_video_script_generator.json](https://www.youtube.com/watch?v=7WsmUlbyjMM) - Generates a short-form video script using AI based on scraped news stories, optimized for virality and engagement.
- [twitter_x_scraping.json](https://youtu.be/otK0ILpn4GQ) - Multiple approaches to scrape tweets from Twitter/X using Apify, then saves tweet data (ID, URL, text, engagement metrics) to Google Sheets for further analysis or automation.
- [content_repurposing_factory.json](https://www.youtube.com/watch?v=u9gwOtjiYnI) - Repurposes any YouTube video into viral-ready Twitter/X threads and LinkedIn posts using Apify and Claude.
- [reverse_engineer_viral_ai_videos.json](https://youtu.be/qNSBLfb82wM) - Reverse-engineers any Instagram Reel or TikTok into a detailed, shot-by-shot prompt, using Apify and Google Gemini.
- [viral_youtube_video_clipper.json](https://www.youtube.com/watch?v=Yb-mZmvHh-I) - Automatically analyzes any YouTube video, generates up to 8 viral-ready short clips using Vizard AI, filters for the most viral (score greater than 9 out of 10), and shares the best clips with download links to Slack for review and sharing.