# Personal AI Life Coach

A personalized AI life coach built with Khoj AI, featuring custom knowledge base and coaching frameworks.

## Features

- Personalized coaching based on proven frameworks
- Access to curated knowledge base of coaching resources
- Progress tracking and goal setting
- Regular check-ins and accountability
- Voice interactions for natural coaching sessions

## Setup

1. Install Dependencies:
```bash
pip install khoj-assistant
```

2. Configure Environment:
```bash
cp .env.example .env
# Edit .env with your configurations
```

3. Initialize Knowledge Base:
```bash
python scripts/init_knowledge.py
```

4. Start the Coach:
```bash
python scripts/start_coach.py
```

## Knowledge Base Structure

- `/knowledge/frameworks/` - Coaching frameworks and methodologies
- `/knowledge/resources/` - Books, articles, and research papers
- `/knowledge/exercises/` - Practical exercises and activities
- `/knowledge/assessments/` - Assessment tools and questionnaires

## Customization

See `config/coaching_config.yaml` for customizing:
- Coaching styles
- Interaction preferences
- Progress tracking metrics
- Goal setting frameworks

## License

MIT License