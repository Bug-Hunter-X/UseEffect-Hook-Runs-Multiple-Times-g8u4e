# React useEffect Hook Runs Multiple Times

This repository demonstrates a common issue with the React `useEffect` hook where it runs multiple times unexpectedly, even when an empty dependency array is provided.  The issue is resolved by ensuring that the component's state does not trigger unnecessary re-renders.