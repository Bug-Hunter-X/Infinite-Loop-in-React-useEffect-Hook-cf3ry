# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React applications where an infinite loop occurs due to an incorrectly configured `useEffect` hook.  The `useEffect` hook attempts to update the state within its own callback, leading to a continuous re-render and an infinite loop. This example showcases the problematic code and provides a corrected version.