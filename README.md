# React useEffect setInterval Memory Leak
This example demonstrates a common mistake in React: using setInterval within a useEffect hook without proper cleanup. This leads to memory leaks and unexpected behavior because the interval continues even after the component unmounts.
The solution shows how to use the cleanup function in useEffect to stop the interval when the component is unmounted.