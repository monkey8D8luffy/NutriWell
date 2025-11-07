NutriWell AI Coach Chatbot
Live Chatbot: [Insert your Dialogflow Messenger URL here]
GitHub Repo: https://github.com/monkey8D8luffy/NutriWell
Overview
AI-powered virtual nutrition coach built with Google Dialogflow ES. Helps users set fitness goals, get personalized meal plans, and track wellness habits.
Features
25 Intents covering goal setting, meal planning, reminders, and progress tracking
15 Custom Entities with 20+ synonyms each (dietary restrictions, budget, time, etc.)
Rich Responses with meal cards and quick-reply chips
Context-Aware conversation flow
Zero External APIs - 100% Dialogflow native
How to Use
Open the live chatbot link
Click "Set My Goals" to start
Answer 4 quick questions about your goals, diet, budget, and time
Get your personalized meal plan instantly
Set hydration/exercise reminders if desired
Core Intents
SetFitnessGoal → Capture weight loss/muscle gain/maintenance
SetDietaryRestriction → Vegan/vegetarian/gluten-free/keto
SetBudgetPreference → Low/medium/high budget meals
SetTimeAvailability → Very quick/quick/moderate/long prep
RequestMealPlan → Generate 3 meals + snacks
SetHydrationReminder → Activate water alerts
TrackProgress → Log weight/measurements/energy
Deployment
Prerequisites: Google Dialogflow ES account (free tier)
Import: Upload agent ZIP file to Dialogflow
Integrate: Enable Dialogflow Messenger integration
Test: Use "Try It Now" in the integration tab
Deploy: Copy integration code to your website
Limitations
No real-time nutrition database integration
Meal plans are pre-structured variations, not dynamically generated
No user authentication or data persistence across sessions
