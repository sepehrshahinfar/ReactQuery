# 🎭 React Events Manager (React Query Practice)

A complete event management application built to practice advanced **React Query** patterns, state management, and data fetching strategies.

## 🎯 Learning Objectives

### **React Query Mastery**
- Data fetching with `useQuery`
- Mutations with `useMutation`
- Query invalidation & cache management
- Optimistic updates (commented examples)
- Dependent queries & query cancellation

### **Advanced Patterns**
- Custom query hooks
- Error handling strategies
- Loading state management
- Stale time & cache time configurations
- Prefetching with `queryClient`

## 🧩 Key Features

| Component | React Query Usage |
|-----------|-------------------|
| `NewEventsSection` | Basic query with staleTime |
| `FindEventSection` | Search-enabled dependent query |
| `EventDetails` | Single event fetch + delete mutation |
| `EditEvent` | Update mutation with form submission |
| `NewEvent` | Create mutation with invalidation |
| `EventForm` | Image selection with prefetching |

## 🛠️ Technical Stack

- **React Query** v4 (TanStack)
- React Router v6
- Modern React patterns (hooks, composition)
- Error boundary patterns
- Custom HTTP client


## 🚀 Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/react-query-events.git
2. Install dependencies
   npm install
3. Start the development server
   npm run dev
4. to start mock backend
   fisrt npm install in backend folder then npm start
