# React 19 useEffect Infinite Loop Bug

This repository demonstrates a common error in React 19 involving the `useEffect` hook causing an infinite loop.  The issue arises from incorrectly managing dependencies within the `useEffect` dependency array.  The solution shows how to correctly specify the dependencies to prevent unintended re-renders and infinite loops.