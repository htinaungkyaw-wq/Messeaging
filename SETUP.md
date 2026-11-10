# PulseChat - Setup & Deployment Guide

## 1. Supabase Project Configuration
1. Go to [Supabase](https://supabase.com) and create a new project.
2. Open the **SQL Editor** tab in your Supabase dashboard.
3. Paste the complete contents of `supabase.sql` and click **Run**.
4. Go to **Project Settings** -> **API**:
   - Copy your `Project URL`.
   - Copy your `anon` / `public` API Key.

## 2. Frontend Setup
1. Open `index.html`.
2. Locate the Supabase configuration parameters near line 380:
   ```javascript
   const SUPABASE_URL = 'YOUR_SUPABASE_URL';
   const SUPABASE_ANON_KEY = 'YOUR_SUPABASE_ANON_KEY';