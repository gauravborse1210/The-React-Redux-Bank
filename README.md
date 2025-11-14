## The REACT-REDUX Bank

This app is built entirely with React and Redux Toolkit.

It handles customer creation and account operations like deposits, withdrawals, loan requests, and repayments.

Currency conversion is supported via the Frankfurter API. State is managed through two slices—customer and account—with clean reducer logic and async actions.

Redux DevTools are enabled for debugging and state inspection.

The UI updates based on customer creation and shows account controls once active.

Everything is wired through a central Redux store using configureStore.
