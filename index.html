<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SecureBank - Communication Preferences</title>
  <script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    :root {
      --primary-color: #1976d2;
      --primary-dark: #1565c0;
      --accent-color: #4caf50;
      --accent-dark: #388e3c;
      --background-color: #f5f7fa;
      --card-background: #ffffff;
      --text-primary: #212121;
      --text-secondary: #757575;
      --border-color: #e0e0e0;
      --shadow: 0 4px 20px rgba(0,0,0,0.12);
      --shadow-hover: 0 8px 30px rgba(0,0,0,0.16);
    }
    body {
      margin: 0;
      font-family: 'Roboto', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      background-color: var(--background-color);
      color: var(--text-primary);
    }
    .app {
      max-width: 100%;
      margin: 0 auto;
      min-height: 100vh;
    }
    .header {
      background: linear-gradient(135deg, var(--primary-color) 0%, var(--primary-dark) 100%);
      color: white;
      text-align: center;
      padding: 1.5rem 1rem;
      position: relative;
      box-shadow: var(--shadow);
    }
    .logo {
      font-size: 1.5rem;
      font-weight: 700;
      margin: 0 0 0.5rem 0;
    }
    .subtitle {
      margin: 0;
      opacity: 0.9;
      font-size: 0.95rem;
    }
    .user-avatar {
      position: absolute;
      top: 1rem;
      right: 1rem;
      width: 40px;
      height: 40px;
      background: rgba(255,255,255,0.2);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.2rem;
    }
    .main {
      padding: 1rem;
    }
    .section {
      margin-bottom: 1.5rem;
      background: var(--card-background);
      border-radius: 16px;
      padding: 1.5rem;
      box-shadow: var(--shadow);
      transition: box-shadow 0.3s ease;
    }
    .section:hover {
      box-shadow: var(--shadow-hover);
    }
    .section h2 {
      margin: 0 0 0.75rem 0;
      color: var(--text-primary);
      font-size: 1.3rem;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }
    .section-desc {
      margin: 0 0 1rem 0;
      color: var(--text-secondary);
      font-size: 0.9rem;
    }
    .user-info {
      display: grid;
      gap: 1rem;
    }
    .user-field {
      display: flex;
      flex-direction: column;
      gap: 0.25rem;
    }
    .user-field label {
      font-size: 0.85rem;
      color: var(--text-secondary);
      font-weight: 500;
    }
    .user-field input {
      padding: 0.75rem;
      border: 1px solid var(--border-color);
      border-radius: 8px;
      font-size: 1rem;
      transition: border-color 0.2s;
    }
    .user-field input:focus {
      outline: none;
      border-color: var(--primary-color);
      box-shadow: 0 0 0 2px rgba(25, 118, 210, 0.2);
    }
    .category {
      margin-bottom: 1rem;
      border: 1px solid var(--border-color);
      border-radius: 12px;
      overflow: hidden;
      transition: all 0.3s ease;
    }
    .category:hover {
      transform: translateY(-2px);
      box-shadow: var(--shadow-hover);
    }
    .category-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 1rem;
      background: #f8f9fa;
      cursor: pointer;
      transition: background 0.2s;
      user-select: none;
    }
    .category-header:hover {
      background: #e9ecef;
    }
    .category-header input[type="checkbox"] {
      display: none;
    }
    .toggle-slider {
      position: relative;
      width: 54px;
      height: 30px;
      background: #ddd;
      border-radius: 15px;
      margin-right: 1rem;
      transition: background 0.3s ease;
      display: flex;
      align-items: center;
      padding: 3px;
    }
    .toggle-slider::before {
      content: '';
      position: absolute;
      top: 3px;
      left: 3px;
      width: 24px;
      height: 24px;
      background: white;
      border-radius: 50%;
      transition: transform 0.3s cubic-bezier(0.4, 0, 0.2, 1);
      box-shadow: 0 2px 4px rgba(0,0,0,0.2);
    }
    .category-header input:checked + .toggle-slider {
      background: var(--accent-color);
    }
    .category-header input:checked + .toggle-slider::before {
      transform: translateX(24px);
    }
    .category-icon {
      margin-right: 0.75rem;
      font-size: 1.2rem;
      color: var(--primary-color);
    }
    .toggle-label {
      flex: 1;
      font-weight: 600;
      color: var(--text-primary);
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }
    .methods {
      padding: 1rem;
      background: var(--card-background);
      transition: all 0.3s ease;
    }
    .method-checkbox {
      display: flex;
      align-items: center;
      cursor: pointer;
      padding: 0.5rem 0;
      transition: background 0.2s;
      border-radius: 8px;
      margin-bottom: 0.25rem;
    }
    .method-checkbox:hover {
      background: #f8f9fa;
    }
    .method-icon {
      margin-right: 0.75rem;
      font-size: 1.1rem;
      color: var(--text-secondary);
      width: 20px;
      text-align: center;
    }
    .method-checkbox input[type="checkbox"] {
      margin-right: 0.75rem;
      accent-color: var(--primary-color);
      transform: scale(1.2);
    }
    .checkmark {
      width: 20px;
      height: 20px;
      border: 2px solid var(--border-color);
      border-radius: 4px;
      margin-right: 0.75rem;
      position: relative;
      transition: all 0.3s ease;
      flex-shrink: 0;
    }
    .method-checkbox input:checked + .checkmark {
      background: var(--primary-color);
      border-color: var(--primary-color);
    }
    .method-checkbox input:checked + .checkmark::after {
      content: '\f00c';
      font-family: 'Font Awesome 6 Free';
      font-weight: 900;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: white;
      font-size: 12px;
    }
    .method-label {
      font-weight: 500;
      color: var(--text-primary);
    }
    .submit-btn {
      width: 100%;
      background: linear-gradient(135deg, var(--primary-color) 0%, var(--primary-dark) 100%);
      color: white;
      border: none;
      padding: 1.25rem;
      border-radius: 12px;
      font-size: 1.1rem;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
      position: relative;
      overflow: hidden;
    }
    .submit-btn:hover {
      transform: translateY(-2px);
      box-shadow: var(--shadow-hover);
    }
    .submit-btn:active {
      transform: translateY(0);
    }
    .submit-btn .loading {
      display: none;
      margin-right: 0.5rem;
    }
    .submit-btn.loading .loading {
      display: inline-block;
      animation: spin 1s linear infinite;
    }
    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
    .success-message {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background: linear-gradient(135deg, var(--accent-color) 0%, var(--accent-dark) 100%);
      color: white;
      padding: 1.5rem 2.5rem;
      border-radius: 16px;
      font-weight: 600;
      z-index: 1000;
      box-shadow: var(--shadow-hover);
      animation: fadeIn 0.3s ease;
      display: flex;
      align-items: center;
      gap: 0.75rem;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translate(-50%, -60%); }
      to { opacity: 1; transform: translate(-50%, -50%); }
    }
    .fade-enter-active, .fade-leave-active {
      transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
    }
    .fade-enter-from, .fade-leave-to {
      opacity: 0;
      transform: translateY(10px);
    }
    .secure-footer {
      text-align: center;
      padding: 1rem;
      color: var(--text-secondary);
      font-size: 0.8rem;
      background: var(--card-background);
      box-shadow: var(--shadow);
    }
    @media (max-width: 480px) {
      .main {
        padding: 0.5rem;
      }
      .section {
        padding: 1rem;
        border-radius: 12px;
      }
      .header {
        padding: 1rem;
      }
      .logo {
        font-size: 1.3rem;
      }
    }
  </style>
</head>
<body>
  <div id="app"></div>
  <script>
    const { createApp } = Vue;

    createApp({
      data() {
        return {
          user: {
            email: 'user@example.com',
            phone: '+1 (555) 123-4567',
            address: '123 Main St, Anytown, USA'
          },
          categories: [
            {
              id: 'policy',
              label: 'Policy Updates',
              icon: 'fas fa-gavel',
              enabled: true,
              methods: ['sms', 'email']
            },
            {
              id: 'collections',
              label: 'Collections & Billing',
              icon: 'fas fa-receipt',
              enabled: true,
              methods: ['email', 'mail']
            },
            {
              id: 'transaction',
              label: 'Transactions',
              icon: 'fas fa-exchange-alt',
              enabled: true,
              methods: ['sms', 'email']
            },
            {
              id: 'security',
              label: 'Security Alerts',
              icon: 'fas fa-shield-alt',
              enabled: true,
              methods: ['sms', 'email', 'phone']
            },
            {
              id: 'outreach',
              label: 'Outreach & Support',
              icon: 'fas fa-comment',
              enabled: false,
              methods: ['email']
            },
            {
              id: 'marketing',
              label: 'Marketing & Promotions',
              icon: 'fas fa-bullhorn',
              enabled: false,
              methods: ['email']
            }
          ],
          availableMethods: [
            { id: 'sms', label: 'SMS', icon: 'fas fa-comment-sms-outline' },
            { id: 'email', label: 'Email', icon: 'fas fa-envelope' },
            { id: 'mail', label: 'Postal Mail', icon: 'fas fa-mail-bulk' },
            { id: 'phone', label: 'Phone Call', icon: 'fas fa-phone' }
          ],
          isSubmitting: false,
          showSuccess: false
        };
      },
      methods: {
        async submitPreferences() {
          this.isSubmitting = true;
          // Simulate API call
          await new Promise(resolve => setTimeout(resolve, 1500));
          const preferences = this.categories.map(category => ({
            id: category.id,
            enabled: category.enabled,
            methods: category.enabled ? category.methods : []
          }));
          console.log('Submitted Preferences:', {
            user: { ...this.user },
            preferences
          });
          this.isSubmitting = false;
          this.showSuccess = true;
          setTimeout(() => { this.showSuccess = false; }, 3000);
        }
      },
      template: `
        <div class="app">
          <header class="header">
            <div class="logo">SecureBank</div>
            <p class="subtitle">Manage your communication preferences securely</p>
            <div class="user-avatar">
              <i class="fas fa-user"></i>
            </div>
          </header>
          <main class="main">
            <section class="section">
              <h2><i class="fas fa-user-edit"></i> Your Contact Information</h2>
              <div class="user-info">
                <div class="user-field">
                  <label>Email</label>
                  <input type="email" v-model="user.email" placeholder="Enter your email">
                </div>
                <div class="user-field">
                  <label>Phone</label>
                  <input type="tel" v-model="user.phone" placeholder="Enter your phone number">
                </div>
                <div class="user-field">
                  <label>Address</label>
                  <input type="text" v-model="user.address" placeholder="Enter your mailing address">
                </div>
              </div>
            </section>
            <section class="section">
              <h2><i class="fas fa-cog"></i> Communication Topics</h2>
              <p class="section-desc">Select topics and preferred delivery methods. All communications are encrypted for your security.</p>
              <div class="categories">
                <div v-for="category in categories" :key="category.id" class="category">
                  <label class="category-header">
                    <input type="checkbox" v-model="category.enabled" :id="category.id">
                    <span class="toggle-slider"></span>
                    <div class="toggle-label">
                      <i :class="category.icon" class="category-icon"></i>
                      {{ category.label }}
                    </div>
                  </label>
                  <transition name="fade">
                    <div v-if="category.enabled" class="methods">
                      <label v-for="method in availableMethods" :key="method.id" class="method-checkbox">
                        <input type="checkbox" v-model="category.methods" :value="method.id" :id="method.id + '-' + category.id">
                        <span class="checkmark"></span>
                        <i :class="method.icon" class="method-icon"></i>
                        <span class="method-label">{{ method.label }}</span>
                      </label>
                    </div>
                  </transition>
                </div>
              </div>
            </section>
            <button @click="submitPreferences" :class="{ loading: isSubmitting }" class="submit-btn">
              <i v-if="isSubmitting" class="fas fa-spinner loading"></i>
              <span v-else>Save Preferences</span>
              <i class="fas fa-lock" style="margin-left: 0.5rem; opacity: 0.8;"></i>
            </button>
          </main>
          <div v-if="showSuccess" class="success-message">
            <i class="fas fa-check-circle"></i>
            Preferences updated securely!
          </div>
          <footer class="secure-footer">
            <p>Your security is our priority. All data is protected with bank-grade encryption.</p>
          </footer>
        </div>
      `
    }).mount('#app');
  </script>
</body>
</html>
